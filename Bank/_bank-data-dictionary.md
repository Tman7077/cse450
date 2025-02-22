# Data Dictionary

We run campaigns periodically. In each campaign, we select a random set of customers, some of which we have already contacted in a previous campaign.

This dataset contains a random set of customers we'd like to target. Some of them have been contacted previously, others haven't been. You can tell how long its been since they were contacted by looking at the `pdays` field and the number of times we've contacted them before by looking at the `previous` field. The `poutcome` field will tell you whether or not the last contact resulted in a successful outcome.

We also have some information about the general economic conditions of the country at the time we last contacted each customer in the sample.

## Client data

`age` *(numeric)*: Age.

`job` *(categorical)*: Type of job.
- **Values**: `admin.`, `blue-collar`, `entrepreneur`, `housemaid`, `management`, `retired`, `self-employed`, `services`, `student`, `technician`, `unemployed`, `unknown`

`marital` *(categorical)*: Marital status.
- **Values**: `divorced`, `married`, `single`, `unknown`
- `divorced` means divorced or widowed.

`education` *(categorical)*: Completed education level.
- **Values**: `basic.4y`, `basic.6y`, `basic.9y`, `high.school`, `illiterate`, `professional.course`, `university.degree`, `unknown`

`default` *(categorical)*: Has credit in default?
- **Values**: `no`, `yes`, `unknown`

`housing` *(categorical)*: Has housing loan?
- **Values**: `no`, `yes`, `unknown`

`loan` *(categorical)*: Has personal loan?
- **Values**: `no`, `yes`, `unknown`

## Related with the last contact of the current campaign

`contact` *(categorical)*: Contact communication type.
- **Values**: `cellular`, `telephone`

`month` *(categorical)*: Last contact month of year.
- **Values**: `jan`, `feb`, `mar`, . . ., `nov`, `dec`

`dayofweek` *(categorical)*: Last contact day of the week.
- **Values**: `mon`, `tue`, `wed`, `thu`, `fri`

## Other attributes

`campaign` *(numeric)*: Number of contacts performed during this campaign and for this client.
- Includes last contact.

`pdays` *(numeric)*: Number of days that passed by after the client was last contacted from a previous campaign.
- 999 means client was not previously contacted.

`previous` *(numeric)*: Number of contacts performed before this campaign and for this client.

`poutcome` *(categorical)*: Outcome of the previous marketing campaign.
- **Values**: `failure`, `nonexistent`, `success`

## Social and economic context attributes

`emp.var.rate` *(numeric)*: Employment variation rate
- Quarterly indicator.

`cons.price.idx` *(numeric)*: Consumer price index
- Monthly indicator.

`cons.conf.idx` *(numeric)*: Consumer confidence index
- Monthly indicator.

`euribor3m` *(numeric)*: Euribor 3 month rate
- Daily indicator.

`nr.employed` *(numeric)*: Number of employees
- Quarterly indicator.

## Output variable

`y` *(binary)*: Has the client subscribed a term deposit?
- **Values**: `yes`, `no`

## Missing attribute values

There are several missing values in some categorical attributes, all coded with the `unknown` label. These missing values can be treated as a possible class label or using deletion or imputation techniques.  
