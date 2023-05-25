* **Bayes' Theorem** is a mathematical formula used to calculate conditional probability. 
* **Conditional probability** refers to the probability of an event occurring given that another event has already occurred. 
* The theorem is named after 18th-century mathematician Thomas Bayes.
* In Bayesian statistics, **prior probability** is the probability of an event before new data is collected. 
* **Posterior probability** is the updated probability of an event based on new data, calculated using Bayes' theorem.
* Bayes' theorem is the foundation of the field of Bayesian statistics, also known as Bayesian inference, which is a method for analyzing and interpreting data. 
* The theorem is applied in various fields such as artificial intelligence, medical testing, financial risk assessment, product recommendation systems, and customer feedback analysis.
* Basic formulation of Bayes' theorem: Probability of A given B equals the probability of A multiplied by the probability of B given A, divided by the probability of B.
* The theorem takes into account both the conditional probability of B given A and the conditional probability of A given B.
* Bayes' theorem helps you update the prior probability based on new data to find out the posterior probability.

* An expanded version of Bayes' theorem exists for certain situations where you don't know the probability of event B.
* The expanded theorem: Probability of event A given event B equals the probability of B given A, multiplied by the probability of A, divided by [the probability of B given A, times the probability of A plus the probability of B given not A, multiplied by the probability of not A].
* The expanded theorem is often used to evaluate tests such as medical diagnostic tests, quality control tests, or software tests, taking into account the probability of testing errors known as false positives and false negatives.
* **False positives**: a test result that incorrectly indicates presence of a condition. 
* **False negatives**: a test result that incorrectly indicates absence of a condition.

* **Basic Bayes' Theorem** is represented by the formula:  
    * P(A|B) = [P(B|A) * P(A)] / P(B)
    * Where:
        * P(A|B) is the posterior probability: the probability of event A occurring given that B is true.
        * P(B|A) is the likelihood: the probability of event B occurring given that A is true.
        * P(A) is the prior probability: the probability of event A occurring.
        * P(B) is the evidence: the probability of event B occurring.

* The **Expanded Bayes' Theorem** is represented by the formula:  
    * P(A|B) = [P(B|A) * P(A)] / {P(B|A) * P(A) + P(B|~A) * P(~A)}
    * Where:
        * P(A|B) is the posterior probability: the probability of event A occurring given that B is true.
        * P(B|A) is the likelihood: the probability of event B occurring given that A is true.
        * P(A) is the prior probability: the probability of event A occurring.
        * P(B|~A) is the false alarm rate: the probability of event B occurring given that A is not true.
        * P(~A) is the complement of the prior probability: the probability of event A not occurring.
