# Attrition clients bancaire
#### Churn for Bank Customers

Les données ont été récupérés depuis "Kaggle", et "copier/coller" tel quel, c'est pour cela que la présentation de la problématique est en anglais mais le reste de l'analyse sera détaillée en Français.
source : https://www.kaggle.com/datasets/mathchi/churn-for-bank-customers?resource=download

### A propos des données (About the dataset) : 

##### Content
RowNumber —corresponds to the record (row) number and has no effect on the output. <br>
CustomerId—contains random values and has no effect on customer leaving the bank. <br>
Surname—the surname of a customer has no impact on their decision to leave the bank. <br>
CreditScore—can have an effect on customer churn, since a customer with a higher credit score is less likely to leave the bank. <br>
Geography—a customer’s location can affect their decision to leave the bank. <br>
Gender—it’s interesting to explore whether gender plays a role in a customer leaving the bank. <br>
Age—this is certainly relevant, since older customers are less likely to leave their bank than younger ones. <br>
Tenure—refers to the number of years that the customer has been a client of the bank. Normally, older clients are more loyal and less likely to leave a bank. <br>
Balance—also a very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances. <br>
NumOfProducts—refers to the number of products that a customer has purchased through the bank. <br>
HasCrCard—denotes whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank. <br>
IsActiveMember—active customers are less likely to leave the bank. <br>
EstimatedSalary—as with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries. <br>
Exited—whether or not the customer left the bank. <br>

##### Acknowledgements
As we know, it is much more expensive to sign in a new client than keeping an existing one.

It is advantageous for banks to know what leads a client towards the decision to leave the company. <br>

Churn prevention allows companies to develop loyalty programs and retention campaigns to keep as many customers as possible.

##### Comprendre et formaliser le besoin

La problématique mise en avant concerne un problème de <b>"churn"</b>, également appelé <b>"customer attrition"</b> en anglais, soit l'attrition client en français (ou taux de perte de clients).
Sur internet, nous pouvons trouver une définition de l'attrition : <br> 
``"L'attrition est une notion marketing qui se caractérise par l'abandon d'une marque, d'un produit ou d'un service de la part de clients existants"``

Sur Kaggle, il est également indiqué <b>qu'il peut être plus coûteux de trouver de nouveau client plutôt que de garder un client déjà existant</b>. Le "plus coûteux" n'est pas forcément une problématique économique mais aussi d'énergie / d'effort pour les conseillers bancaires, pour attirer de nouveau client, du fait entre autre de l'exigence des clients sur les attentes qu'ils ont de leur banque. Un article de la BPCE parle des ``"4 tendances clés qui changent l'expérience client dans le secteur bancaire"`` (https://blogrecrutement.bpce.fr/4-tendances-cles-changent-experience-client-dans-secteur-bancaire) 
