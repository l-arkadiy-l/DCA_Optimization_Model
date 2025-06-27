# DCA Optimization Model

The initial task I got in one of the interview and it looks like this:

---

**Practical Assignment**

Test an investment strategy of buying the Japanese index.

Imagine a scenario where an investor started purchasing the index every Monday at market open, beginning on **01/01/1990**, investing the **same amount in USD** each time.

Answer the following questions:

1. What would be the **total return in USD** by the last day of the available data?
2. How much time would the investment spend **in drawdown**?
3. Without drastically changing the investment method, apply a couple of techniques to **increase the return** and **reduce drawdown duration**.

Present your results in a **Jupyter Notebook**.
Any additional analysis or results will be considered a plus.

---

DCA strategy have 393% investment return. 

For improve this number I have created 3 strategy:

    1. Buy more of the index during drawdowns (+353% IR)
    2. Market seasonality strategy (+395% IR)
    3. MA26 strategy (+422% IR)
