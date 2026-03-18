

#  Convexity measures movement and magnifitude but not dicretion.

### Duration revisited

As a refresher, a bond's duration is defined as the negative of its first derivative with respect to its yield to maturity ($\text{ytm}$), divided by the bond's value. Duration forms the basis of the first-order Taylor series approximation for changes in bond values due to changes in $\text{ytm}$:

$$\text{Change in Value} \approx -\Delta \text{ytm} \times \text{Modified Duration}$$

In terms of the mathematical components:

$$V(\text{ytm}+\Delta \text{ytm})-V(\text{ytm})\approx -\Delta \text{ytm}\times\sum_{i=1}^{N}t_i\times Cash\ Flow_{t_i} \times e^{-\text{ytm}\times t_i}$$

### Introducing Convexity via Taylor Series Expansion

The general form of a Taylor series expansion is:

$$f(x+\Delta x)\approx \sum\_{i=1}^{N}\frac{d^{i}f(x)}{dx^{i}}\times\frac{1}{i\!}\Delta x^{i}$$

Convexity is defined using the second-order Taylor series expansion:

$$f(x+\Delta x)\thickapprox f(x)+\frac{df(x)}{dx}\times\Delta x+\frac{1}{2}\frac{d^{2}f(x)}{dx^{2}}\times\Delta x^{2}$$

Applying this second-order expansion to the present value formula yields a more accurate estimate of the change in bond value:

$$V(\text{ytm}+\Delta \text{ytm})-V(\text{ytm})\approx -\Delta \text{ytm}\times\sum_{i=1}^{N}t_i\times Cash\ Flow_{t_i} \times e^{-\text{ytm}\times t_i}+ \frac{\Delta \text{ytm}^{2}}{2}\times\sum_{i=1}^{N}t_i^{2}\times Cash\ Flow_{t_i} \times e^{-\text{ytm}\times t_i}$$

### The Convexity Formula

Mirroring the definition of duration, convexity is calculated by dividing the bond's second derivative with respect to $\text{ytm}$ by the bond's value:

$$Convexity =\frac{\sum_{i=1}^{N}t_i^{2}\times Cash\ Flow_{t_i} \times e^{-\text{ytm}\times t_i}}{V(\text{ytm})}$$

<br>

## Convexity and Duration Predict Bond Price Changes.

The change in bond price ($\Delta V$) can be predicted using a second-order Taylor expansion that incorporates both duration and convexity, as shown below:

<br>

$$\Delta V \approx (Duration \times -\Delta \text{ytm} + \frac{1}{2} \times Convexity \times \Delta \text{ytm}^{2}) \times V(\text{ytm})$$

<br>

The change in yield to maturity ($\Delta \text{ytm}$) can be broken down into its expected value ($E(\Delta \text{ytm})$) and its deviation from that expected value:

<br>

$$\Delta \text{ytm} = (\Delta \text{ytm} - E(\Delta \text{ytm}) + E(\Delta \text{ytm})$$

<br>

The squared change in yield to maturity is:

<br>

$$\Delta \text{ytm}^{2} = (\Delta \text{ytm} - E(\Delta \text{ytm})^{2} + E(\Delta \text{ytm})^{2}+2 \times (\Delta \text{ytm} - E(\Delta \text{ytm}) \times E(\Delta \text{ytm})$$

<br>

Consequently, the expected value of the squared change in yield to maturity is:

<br>

$$E(\Delta \text{ytm}^{2}) = \sigma_{\Delta \text{ytm}}^{2}+E(\Delta \text{ytm})^{2}$$

<br>

Substituting the expected values into the Taylor expansion, the expected change in the bond's value is:

<br>

$$E(\Delta V) =(Duration \times -E(\Delta \text{ytm})+ \frac{1}{2} \times Convexity \times (\sigma_{\Delta \text{ytm}}^{2}+E(\Delta \text{ytm})^{2}) \times V(\text{ytm})$$

<br>

The second-order Taylor expansion reveals two primary effects on the expected bond price changes:

<br>


*  $\qquad\textbf{Direction:}\quad   -Duration\times E(\Delta \text{ytm})$
*  $\qquad\textbf{Volatility:}\quad  \frac{1}{2}\times Convexity\times (\sigma^{2}_{\Delta \text{ytm}}+E(\Delta \text{ytm})^2)$


