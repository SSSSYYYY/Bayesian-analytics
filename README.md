# Bayesian-analytics


Three frameworks of probability
1. classical : outcomes that are equally likely have equal probabilities.

This Classical approach works really well and we have equally likely outcomes or well-defined equally likely outcomes. That's very difficult to apply in any of these other cases.


2.Frequentist : requires to have a hypothetical infinite sequence of events, and then we look at the relevant frequency, in that hypothetical infinite sequence.

This approach works great when we can define a hypothetical infinite sequence. But then we can ask other questions, and they become more complicated under this approach. The probability is derived from a relative frequency perspective.

3.Bayesian  :  is one of personal perspective.

Coherence: probabilities must follow all the standard rules of probability, If you don't follow all the rules for probability, then you can be incoherent, which leads to a case for someone to construct a series of bets where you're guaranteed to lose money. This is referred to as Dutch book. If you do follow all the rules, and you follow the framework of Bayesian statistics, then you can be guaranteed to be coherent.


Bayes:
If independence
P(A|B) = P(A)
then P(A U B) = P(A)P(B)


Distributions:
Discrest
 Bernoulli : X ~ B(p)
             P(X=1) = p
             P(X=0) = 1-p
             X can take only 1 or 0
             E[X] = p
             Var(X) = p(1-p)
 
 Binomial : X ~ Bin(n,p)
            E[X] = np
            Var(X) = np(1-p)
            
Continuoes 
 Uniform : X ~ U[0.1]
           F(x) = ...
           
           E[X] = integration xf(x) dx
 
 Exponential: X ~ Exp(lambda)
             f(x|lambda) = 
             E[X] = 1/lambda 
             Var(X) = 1/ lambda^2
             
 Normal : X ~ N(u, sigma^2)     
          E[X] = u
          Var(X) = sigma^2
 
 
