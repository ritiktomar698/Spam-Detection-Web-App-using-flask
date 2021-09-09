<h1>Spam Classification using Naive Bayes</h1>Spam has become a growing problem over the years. About 70% of all email is spam. As with web extensions, the problem of email
spam is also growing as well. It was found that an average of 10 days a year was compromised in spam processing.
Spam is a costly issue which can cost a lot in the following years to lower bandwidth providers. Spam is an important issue that
still attacks the presence of email. Therefore, it is very important to distinguish junk e-mail from various methods that are
recommended to identify and classify e-mail messages as spam or non-spam or e-mail, and to find out the success rate of the
algorithm.
<h2>Naïve Bayes:</h2>
A naive Bayes classifier is a simple probabilistic classifier with strong assumptions of independence. Simply put,
a naive bayes classifier assumes that the presence / absence of a particular property of a class is not related to the presence / absence
of any other feature, considering the class variable as a function of the Class Probability Model, Trained in a supervised learning
environment. An advantage of the naive bayes classification is that it requires only a small amount of training data to estimate the
parameters required for classification. The Bayesian classification assumes that the data belongs to a particular class. We then
calculate the probability that the assumption is true. Bayesian classmates are basically statistical classifiers, that is, they can predict
probabilities of class membership, such as the probability that a given test belongs to a particular class.<br>
The naïve technique of Bayes is based on a Bayesian approach, it is therefore a simple, clear and fast classifier. Before reaching
the main term of the Bayes theorem, we will first analyze certain terms used in the theorem.<ul>
  <li>P (A) is the probability that event A occurs. 
  <li>P (A / B) is the probability that event A occurs because event B has already occurred or we can define it as the conditional
probability of A as a function of the condition that B has already occurred.</ul>
    The Bayes theorem is defined in Equation 1.<br>
P (A/B) = P (B/A) P (A) P (B) ---------(1)
<br>If we consider OBJX as an object to be classified with the likelihood of belonging to one of classes CLS1, CLS2, CLS3,
etc. By calculating Prob (CLSi / OBJX). Once these probabilities have been calculated for all classes, we simply assign OBJX to
the class with the highest probability.<br>
Prob (CLSi / OBJX) = [Prob (OBJX / CLSi) Prob (CLSi)] / Prob (OBJX) -------(2)<br>
Where Prob (CLSi / OBJX) is the probability that the object OBJX belongs to a class CLSi, Prob (OBJX / CLSi) is the probability
of obtaining attribute values OBJX if we know that it belongs to class CLSi Prob (CLSi) is the probability of an object belonging
to a class CLSi without any other information, and Prob (OBJX) is the probability of obtaining OBJX attribute values regardless of
the class to which the object belongs.
