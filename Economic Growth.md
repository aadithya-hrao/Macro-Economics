---
tags:
  - "#notes"
  - "#economics"
index: 2
---
# Introduction
## Purpose of Economic Growth
- **Raising Standards of Living**: Economic growth aims to improve people's well-being by providing access to tools, equipment, education, and healthcare.
- **Human Element in Economics**: Economic development focuses on improving lives, particularly in developing countries.

## Measuring Economic Growth
- **GDP per Capita**: Represents three key aspects:
  1. **Average Expenditure per Person** – Reflects the standard of living based on goods and services consumption.
  2. **Average Income per Person** – Higher income allows for more purchases.
  3. **Productivity (Output per Person)** – More productivity leads to more income and higher living standards.

## Factors of Growth (Determinants of Productivity)
1. **Physical Capital**: 
   - Tools, machinery, factories enhance worker productivity.
   - Example: A sledgehammer vs. a jackhammer for breaking concrete.

2. **Human Capital**: 
   - **Skills & Education**: Higher education/training increases market value.
   - **Health**: Healthy workers are more productive.

3. **Natural Resources & Energy**:
   - Access to energy sources (oil, gas, solar, wind) is critical.
   - Cheap, abundant energy enhances productivity.
   - **Balance with Environment**: Clean energy alternatives help reduce environmental impact.

4. **Entrepreneurship**:
   - Risk-taking innovators drive productivity and efficiency.
   - Example: Bill Gates (Microsoft), Elon Musk, Jeff Bezos, Mark Zuckerberg.

5. **Social & Legal Framework**:
   - Policies, laws, and institutions affect productivity.
   - Social media and digital platforms impact organization and communication.

6. **Technology (Key to Long-Term Growth)**:
   - Enhances all other growth factors.
   - **Physical Capital**: More advanced tools improve efficiency.
   - **Human Capital**: Medical advancements improve health; digital learning expands education.
   - **Natural Resources**: Tech enables cleaner energy extraction and utilization.
   - **Entrepreneurship**: Tech fuels new industries and opportunities.
   - **Social Framework**: Social media and AI influence governance and communication.
   - **Self-Sustaining**: New technologies enable further technological advances.

# Growth Formula and Solow Growth Model

## Growth Formula and Compounding Effects
- Small differences in growth rates lead to significant long-term effects.
- GDP per capita formula:
  $$ 
  Y_t = Y_0 (1 + g)^t 
  $$
  where:
  - $Y_t$ = GDP per capita at time $t$,
  - $Y_0$ = initial GDP per capita,
  - $g$ = growth rate,
  - $t$ = number of years elapsed.

- Example projections for U.S. GDP per capita (2021 baseline: $69,231$):
  - **1% growth** → $103,000$ in 40 years.
  - **2% growth** → $153,000$ in 40 years.
  - **3% growth** → $226,000$ in 40 years.
- Developed economies average **~2% growth**.

## General GDP Production Function
- GDP ($Y$) depends on multiple factors:
  $$ 
  Y = A\ f(K, L, H, R) 
  $$
  where:
  - $A$ = total factor productivity (TFP) (tech, entrepreneurship, legal framework),
  - $K$ = capital (machines, factories),
  - $L$ = labor (number of workers),
  - $H$ = human capital (education, skills, health),
  - $R$ = natural resources.

- **GDP per capita** formula:
  $$ 
  \frac{Y}{\text{Population}} = \frac{Y}{L} \times \frac{L}{\text{Population}} 
  $$
  - **Ways to increase GDP per capita**:
    - Increase **labor force participation**.
    - Increase **average labor productivity**.

## Cobb-Douglas Production Function
- **Explicit functional form**:
  $$ 
  Y = A K^\alpha L^{1-\alpha} 
  $$
  where:
  - $\alpha$ is a parameter (typically $\approx 1/3$),
  - **Key properties**:
    - **Diminishing marginal productivity** ($K$ and $L$ increase output at a decreasing rate).
    - **Constant returns to scale** (doubling $K$ and $L$ doubles output).

- **Per Capita Form**:
  $$ 
  y = A k^\alpha 
  $$
  where:
  - $y = \frac{Y}{L}$ = GDP per worker,
  - $k = \frac{K}{L}$ = capital per worker.

- **Interpretation**:
  - Productivity depends on **technology** ($A$) and **machines per worker** ($k$).
  - **Diminishing marginal productivity of capital**:
    - As capital per worker increases, productivity increases at a **decreasing rate**.
    - **Marginal product of capital** is always **positive but declining**.

# Consumption and Investment

- **GDP per Capita & Productivity**
  - GDP per capita ($y$) represents average income, expenditure, and productivity.
  - Two expressions:
    - Expenditure side: $y = consumption\ +\ investment$
    - Productivity side: $y = A k^\alpha$

- **Income Allocation & Savings**
  - Income is split between consumption ($c$) and investment ($i$).
  - Savings is defined as:  
    $$\text{Savings} = y - c$$  
    and equals investment.
  - The savings rate ($s$, between 0 and 1) gives:  
    $$i = s\,y$$  
    and consumption is:  
    $$c = (1-s)y$$

- **Model Assumptions**
  - Closed economy: no government spending ($g$) or net exports ($nx$), so GDP simplifies to $y = c + i$.

- **Investment & the Capital-Labor Ratio**
  - Physical capital (machines) is acquired through investment.
  - Productivity depends on the capital-labor ratio ($k = K/L$):  
    $$y = A k^\alpha$$
  - Investment in terms of $k$:  
    $$i = s\,A\,k^\alpha$$

- **Net Investment & Effective Depreciation**
  - Net change in the capital-labor ratio is given by:  
    $$\Delta k = i - (\eta + \delta) k$$  
    where:
    - $\eta$ is the population growth rate,
    - $\delta$ is the depreciation rate.
  - Effective depreciation is $(\eta + \delta) k$.

- **Steady State Analysis**
  - Steady state is reached when net investment is zero:  
    $$i = (\eta+\delta) k$$
  - Substituting $i = s\,A\,k^\alpha$, we get:  
    $$s\,A\,k^\alpha = (\eta+\delta) k$$  
    which simplifies to:  
    $$k^{1-\alpha} = \frac{sA}{\eta+\delta}$$
  - Solving for $k$:  
    $$k^* = \left(\frac{sA}{\eta+\delta}\right)^{\frac{1}{1-\alpha}}$$

- **Growth Rate of the Capital-Labor Ratio**
  - The growth rate is calculated as:  
    $$\frac{\Delta k}{k} = sA\,k^{\alpha-1}\ -\ (\eta+\delta)$$
  - It comprises:
    - A positive term from investment: $sA\,k^{\alpha-1}$
    - A negative term from effective depreciation: $(\eta+\delta)$
  - The steady state is the point where these two effects balance, resulting in zero net growth.

# Solow Growth Model: Convergence and Steady States

## Convergence Theories

### Unconditional Convergence

- **Theory**: Poor countries will naturally catch up to rich countries.
- **Example**: UK vs. Brazil
    - Different starting points and growth rates based on distance from steady state.
- **Empirical Issues**:
    - Steady states differ across countries due to savings rates, technology, and institutions.
    - Expected negative relationship between GDP per capita and growth rate not consistently observed.

### Conditional Convergence

- Poor countries catch up only if they share similar characteristics.
- **Empirical Support**:
    - OECD countries showed expected convergence patterns.
    - US states exhibited convergence due to similar institutions and policies.
- **Key Factors Affecting Steady States**:
    - Savings rates
    - Total Factor Productivity (TFP): Innovation, legal framework, healthcare, education, skill levels, natural resources

## Historical Growth Perspectives

### Post-WWII Growth Rates (1945–1965)

- **Soviet Union**: 7–8% growth
- **Europe**: 4–5% growth
- **United States**: ~2% growth

### Cold War Growth Dynamics

- Initial misconception: USSR expected to surpass the US
- **Reality**: Rapid growth was temporary, driven by post-war recovery
- **Key Issue**: Diminishing marginal productivity

### Long-Term Outcomes (1965–1991)

- **US & Europe**: Continued ~2% growth, benefiting from market-based innovation
- **USSR Collapse**:
    - Central planning failed to sustain long-term growth
    - Lack of profit incentives reduced innovation
    - Market economies better at encouraging technological progress

## Economic Growth Model

### Cobb-Douglas Production Function

- **Level production function**: $$ Y = A K^\alpha L^{1-\alpha} $$
    
    - $A$: Total Factor Productivity
    - $K$: Physical capital
    - $L$: Labor
    - $\alpha$: Determines diminishing marginal productivity
- **Per capita production function**: $$ y = A k^\alpha $$
    
    - $y$: GDP per capita
    - $k$: Capital per worker

### Steady State Calculation

- **Steady State Formula**: $$ k^* = \left( \frac{s A}{\eta + \delta} \right)^{\frac{1}{1-\alpha}} $$
    - $s$: Savings rate
    - $\eta$: Population growth rate
    - $\delta$: Depreciation rate

## Key Insights

- Unconditional convergence is not universally applicable
- Conditional convergence depends on economic fundamentals
- Growth driven by technology and capital per worker
- Diminishing marginal productivity limits long-term growth rates
- Market economies provide better innovation incentives

## Measuring Economic Growth

- **Standard of Living**: Measured by GDP per capita
- **Growth Mechanism**: Increasing productivity through technology and capital investment

