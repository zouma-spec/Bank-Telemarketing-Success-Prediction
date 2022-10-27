[Read my Medium article here!](https://medium.com/@xiaoruiyuan/machine-learning-for-better-buying-decisions-59108f6fdcfc)
![image](https://user-images.githubusercontent.com/84628470/194738965-3a30cb66-0156-4e5c-8fc7-c7d39e62953e.png)

### Data
| Features                                                  | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| age (numerical)                                              | from 18 to 95 years old                                      |
| job (categorical)                                            | 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown'|
| marital status (categorical)                                 | 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed|
| education (categorical)                                      | "unknown","secondary","primary","tertiary" |
| default (binary)                                              | has credit in default? ("yes","no") |
| balance (numeric)                                             | average yearly balance, in euros                       |
| housing (binary)                                             | has housing loan? ("yes","no")  |                              
| loan(binary)                                                  |has personal loan? ("yes","no")      |
| contact(categorical)                                          | contact communication type ("unknown","telephone","cellular")|
| day(numeric)                                                            |last contact day of the month|
| month(categorical)                                                          |last contact month of year ("jan", "feb", "mar", ..., "nov", "dec")
| campaign(numeric)                                             | number of contacts performed during this campaign and for this client|
| pdays(numeric)                                                 | number of days that passed by after the client was last contacted from a previous campaign (999 means client was not previously contacted)
| previous(numeric)                                                 | number of contacts performed before this campaign and for this client|
| poutcome(categorical)                                       | outcome of the previous marketing campaign ("unknown","other","failure","success")

| Target                            | Description                               |
| --------------------------------- | ----------------------------------------- |
| has the client subscribed a term deposit?(binary)    | (binary: "yes","no")             |
