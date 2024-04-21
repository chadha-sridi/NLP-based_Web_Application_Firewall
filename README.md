# :rocket:NLP-based Web Application Firewall
Web attacks are a significant threat to online security. Traditional WAFs (Rule-based) may struggle to detect certain attacks due to sophisticated <b>obfuscation</b> techniques used by attackers.

<b>Example:</b>
Consider a simple XSS payload:

<b><script>alert('XSS Attack!');</script></b>
<p>Now, observe its obfuscated version, which might evade rule-based WAFs:</p>

<b>%253Cscript%253Ealert%2528%2527XSS%2520Attack%2521%2527%2529%253B%253C%252Fscript%253E</b>
<p>However, Natural Language Processing (NLP) techniques have shown promise in resisting such obfuscation techniques. In this project, we leverage the power of NLP to enhance web security.</p>
<h2>Features:</h2>
<ul>
  <li>Utilizes simple NLP techniques: <b>Bag of Words</b> and <b>TF-IDF</b>.</li>
  <li>Implements multiple machine learning algorithms including Multinomial Naive Bayes, Logistic Regression, Support Vector Machines (SVM), Random Forests, etc.</li>
  <li> Includes code for utilizing <b>fastText</b>, a library for efficient learning of word representations and sentence classification.</li>
</ul>

<h2>Dataset:</h2>
<p>The dataset utilized is CSIC 2010. It comprises of sqli, xss, command injection and path traversal malicious payloads as well as normal http requests. </p>
<p>Link: https://www.kaggle.com/datasets/ispangler/csic-2010-web-application-attacks</p>


    
   
