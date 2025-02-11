java c
FN3142 ZA 
BSc degrees and Diplomas for Graduates in Economics, Management, Finance and the Social Sciences, the Diplomas in Economics and Social Sciences 
Quantitative Finance 
Monday, 22   May 2017   :   10:00 to   13:00
Question 1 
The   probability   density   function   of   the   normal   distribution   is   given   by

where   µ   is   the   mean   and   σ   2      is   the   variance   of the   distribution.
a [7    marks] Assuming   µ    =   0   derive   the   maximum   likelihood   estimate   of   σ   2      given   the   sample   of i.i.d   data   (x1   ,   x2, . .   .   ,   xT   ).
b [8 marks] Now   assume that   xt      is   conditionally normally distributed as N(0,   σt(2))   where
σt(2)   = ω + βσt(2)-1   + αxt(2)-1 
Write down the likelihood function for this model given   a sample of   data (x1   ,   x2, . .   .   ,   xT   ).
c [10    marks] Describe   how   we   can   obtain   estimates   for   {ω,   α,   β}   for   the   GARCH(1,1)   model   and   discuss   estimation   di伍culties.
Question 2 
Consider   the   time   series   process   xt    that   follows
xt      = φxt-1   + σct
where   ct      ~ N   (0, 1)   and   φ   < 1.
a [5 marks] What   is   the   unconditional   mean   of   xt?
b [5 marks] What   is   the   unconditional   variance   of   xt?
c [5 marks] What   is   the   ﬁrst-order   autocorrelation   of   xt?
d [5 marks] What   is   the   second-order   autocorrelation   of   xt?
e [5 marks] Given   a   sample   of   data   (x1   ,   x2, . . . ,   xT   ) you   estimate   the   parameters   of   this process   via   OLS.   Compute   an   analytical   expression   for   the   R2    in   this   regression   and   give   an   interpretation.
Question 3 
a [5    marks] Given   a   loss   function   L,   an   optimal   forecast   is   obtained   by   minimising   the   conditional   expectation   of the   future   loss:
Given   the   quadratic   loss   functionL(y,   ˆ(y)) =   (y   -ˆ(y))2                                                                                                                                                                                                                                       (2)
show   that   the   optimal   forecast   is   the   conditional   mean.
b [5    marks] Describe   how   one   can   test   forecast   optimality   with   Mincer-Zarnowitz   re-   gression.
c [5    marks] Consider   a   forecast   Y(ˆ)τ*       of   a   variable   Yτ .    You   have   100   observations   of   Y(ˆ)τ* and   Yτ      and   run   the   following   regression
Yτ =   Q + βY(ˆ)τ*   + ετ 
and   obtain   the   following   results:
                        Estimate               Std Error
α                   -0.10                       0.02
β                    1.51                       0.30
what   null   hypothesis   should   you   set   up   in   order   to   test   for   forecast   optimality?    Can   this   test   be   conducted   with   the   information   given?
d [10    marks] What   can   be   inferred   from   the   results   table   in   part   (c)?
Question 4 
a [5 marks] What   is   meant   by   serial   correlation?    Give   an   example   of a   process with   zero serial correlation and an example of a process with positive   serial   correlation.
b [10    marks] Malkiel   (1992)   stated   that   a   capital   market   is   e伍cient   if   it   fully   and   correctly re丑ects all relevant information in determining   securities   prices.   Thus,   mar-   ket   e伍ciency   is   deﬁned   with   respect   to   some   information   set   Ωt.   Describe the   three   commonly employed deﬁnitions of market e伍ciency that depend on the   size   of Ωt.
c [10 marks] Which of the following observations could provide evidence against semi-   strong form. market e伍ciency?   In the case of   observations   that could   go   against   market   e伍ciency, explain what additional information would be needed to conduct a rigorous   test.
–    Mutual fund managers do not o代 写FN3142 Quantitative FinanceJava
代做程序编程语言n average make superior returns than the market.
– In a particular year hedge fund managers make superior returns than the market.
– Mutual fund managers do not on average make superior returns than the market. 
– On average hedge fund managers make superior returns   than   the   market.
– Low book-to-market stocks tend to have higher returns than high book-to-market   stocks.
– forming a portfolio that goes long stocks that have had large positive returns over   the previous year and goes short stocks that have had large negative returns over the previous year generates superior returns than the market.
FN3142 ZB 
BSc degrees and Diplomas for Graduates in Economics, Management, Finance and the Social Sciences, the Diplomas in Economics and Social Sciences 
Quantitative Finance 
Monday, 22   May 2017   :   10:00 to   13:00
Question 1 Imagine the following gamble.    First, flip   a fair   coin   to   determine   the   amount   of your   bet:   if heads,   you   bet   $1,   if tails   you   bet   $2.    Second, flip   again:    if heads,   you   win   the   amount   of   your   bet,   if   tails,   you   lose   it.    For   example,   if   you flip   heads   and   then   tails,   you   lose    $1;   if   you flip   tails   and   then   heads   you   win   $2.)   Let   X   be   the   amount   you   bet,   and   let   Y   be   your   net   winnings   (negative   if you   lost).
a [10    Marks] Show   that   the   covariance   between   X   and   Y   is   zero.   b [15 Marks] Show   that   X    and   Y   are   not   independent.
Question 2 
Consider   the   zero-mean   MA(1)   process   Xt      :
Xt      = ut   + δut-1               where   ut      i~.i.d      N(0,   σu(2))
a [5 Marks] Find   E[Xt], Et   [Xt+1],   Et   [Xt+2]
b [5 Marks] Find   √0    =   Var[Xt]
c [15    Marks] Derive    the    autocorrelation    function    (ACF).    Now,    imagine   you    have   a   parameter   estimate   of   δ   = 0.70.    Plot   the   autocorrelation   function   as   a   function   of the   number   of   lags.
Question 3 
a [5    Marks] Assume   daily   returns   that   are   normally   distributed   with   constant   mean   and   variance,   i.e.,   they   are   given   by
Rt+1      = σνt+1
νt+1   i~.i.d   N(0, 1)
where the time   increment   t   + 1   is   1-day.    Derive the   following   formula   for the Value-at-   Risk   at   the   α%   (VaR)   critical   level   and   1-day   horizon.

where   Φ   is   the   standard   normal   cumulative   density   function.
b [10 Marks] Describe   the   ‘historical   simulation’   and   RiskMetrics   approaches   to   mea-   suring   Value-at-Risk.
c [10 Marks] The   expected   shortfall   EStα+1 at the critical level α% and 1-day horizon   can   be   deﬁned   as

Using   the   VaR   formula   from   part      (a)   derive   the   following   formula   for   the   1-day   ex-   pected   shortfall   at   critical   level   α

where φ is the standard normal   probability density function.    Hint:   From the properties   of the   normal   distribution   we   know   that

if   z   is   normally   distributed.
Question 4 a [5 Marks] Roberts (1967) deﬁnes three types of information set available to investors:
(i) weak   form   eflciency;   (ii)   semi-strong form   eflciency;   (iii)   strong   form   eflciency.   Report a deﬁnition for each   of these.
b [5 Marks] To which information set, if any, do   the following variables belong?
– Stock prices today.
– The risk free rate today.
– Next year’s production ﬁgures just approved by a company’s board of directors.
– The nominal size of the short position George Soros has   in   European   equity.
– Stock prices tomorrow.c [5    Marks] What   is   the   eflcient   market   hypothesis   statement   according   to   Malkiel (1992)?
d [10 Marks] Black   (1986) gives an alternative deﬁnition of market eflciency.   What is   it and why is Black’s deﬁnition diflcult   to   test?





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
