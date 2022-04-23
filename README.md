# HierarchicalRegression
 Modelled layered regression



OUTPUT FILES FROM SPSS FILES











NEW FILE.
DATASET NAME DataSet1 WINDOW=FRONT.
GET
  FILE='E:\DATA_JOBS\HierarchicalRegression\impulse_data_A3 (3).sav'.
DATASET NAME DataSet2 WINDOW=FRONT.
CODEBOOK  id [s] sex [n] age [s] i1 [o] i2 [o] i3 [o] impulse [s] rses [s] des [s]
  /VARINFO POSITION LABEL TYPE FORMAT MEASURE ROLE VALUELABELS MISSING ATTRIBUTES
  /OPTIONS VARORDER=VARLIST SORT=ASCENDING MAXCATS=200
  /STATISTICS COUNT PERCENT MEAN STDDEV QUARTILES.




Codebook



Notes
Output Created	23-APR-2022 08:30:21
Comments	
Input	Data	E:\DATA_JOBS\HierarchicalRegression\impulse_data_A3 (3).sav
	Active Dataset	DataSet2
	Filter	<none>
	Weight	<none>
	Split File	<none>
	N of Rows in Working Data File	456
Syntax	CODEBOOK  id [s] sex [n] age [s] i1 [o] i2 [o] i3 [o] impulse [s] rses [s] des [s]
  /VARINFO POSITION LABEL TYPE FORMAT MEASURE ROLE VALUELABELS MISSING ATTRIBUTES
  /OPTIONS VARORDER=VARLIST SORT=ASCENDING MAXCATS=200
  /STATISTICS COUNT PERCENT MEAN STDDEV QUARTILES.
Resources	Processor Time	00:00:00.03
	Elapsed Time	00:00:00.31


[DataSet2] E:\DATA_JOBS\HierarchicalRegression\impulse_data_A3 (3).sav



id
	Value
Standard Attributes	Position	1
	Label	Participant's ID
	Type	Numeric
	Format	F2
	Measurement	Scale
	Role	Input
N	Valid	456
	Missing	0
Central Tendency and Dispersion	Mean	228.50
	Standard Deviation	131.780
	Percentile 25	114.50
	Percentile 50	228.50
	Percentile 75	342.50


sex
	Value	Count	Percent
Standard Attributes	Position	2		
	Label	Biological sex		
	Type	Numeric		
	Format	F1		
	Measurement	Nominal		
	Role	Input		
Valid Values	1	Male	214	46.9%
	2	Female	242	53.1%


age
	Value
Standard Attributes	Position	3
	Label	Age
	Type	Numeric
	Format	F2
	Measurement	Scale
	Role	Input
N	Valid	456
	Missing	0
Central Tendency and Dispersion	Mean	44.90
	Standard Deviation	11.069
	Percentile 25	36.00
	Percentile 50	44.00
	Percentile 75	52.00


i1
	Value	Count	Percent
Standard Attributes	Position	4		
	Label	Item 1		
	Type	Numeric		
	Format	F1		
	Measurement	Ordinal		
	Role	Input		
Valid Values	1		17	3.7%
	2		51	11.2%
	3		47	10.3%
	4		197	43.2%
	5		144	31.6%


i2
	Value	Count	Percent
Standard Attributes	Position	5		
	Label	Item 2		
	Type	Numeric		
	Format	F1		
	Measurement	Ordinal		
	Role	Input		
Valid Values	1		112	24.6%
	2		116	25.4%
	3		71	15.6%
	4		109	23.9%
	5		48	10.5%


i3
	Value	Count	Percent
Standard Attributes	Position	6		
	Label	Item 3		
	Type	Numeric		
	Format	F1		
	Measurement	Ordinal		
	Role	Input		
Valid Values	1		18	3.9%
	2		46	10.1%
	3		54	11.8%
	4		206	45.2%
	5		132	28.9%


impulse
	Value
Standard Attributes	Position	18
	Label	Impulsiveness Scale
	Type	Numeric
	Format	F2
	Measurement	Scale
	Role	Input
N	Valid	456
	Missing	0
Central Tendency and Dispersion	Mean	29.50
	Standard Deviation	9.592
	Percentile 25	22.50
	Percentile 50	28.00
	Percentile 75	36.00


rses
	Value
Standard Attributes	Position	19
	Label	Rosenberg's Self-Esteem Scale
	Type	Numeric
	Format	F2
	Measurement	Scale
	Role	Input
N	Valid	456
	Missing	0
Central Tendency and Dispersion	Mean	14.48
	Standard Deviation	5.927
	Percentile 25	10.00
	Percentile 50	15.00
	Percentile 75	18.00


des
	Value
Standard Attributes	Position	20
	Label	Dispositional Envy Scale
	Type	Numeric
	Format	F2
	Measurement	Scale
	Role	Input
N	Valid	456
	Missing	0
Central Tendency and Dispersion	Mean	25.61
	Standard Deviation	6.308
	Percentile 25	20.00
	Percentile 50	25.00
	Percentile 75	31.00

CODEBOOK  id [s] sex [n] age [s] i1 [o] i2 [o] i3 [o] impulse [s] rses [s] des [s] i4 [o] i5 [o] i6
    [o] i7 [o] i8 [o] i9 [o] i10 [o] i11 [o] i12 [o] i13 [o] i14 [o]
  /VARINFO POSITION LABEL TYPE FORMAT MEASURE ROLE VALUELABELS MISSING ATTRIBUTES
  /OPTIONS VARORDER=VARLIST SORT=ASCENDING MAXCATS=200
  /STATISTICS COUNT PERCENT MEAN STDDEV QUARTILES.




Codebook



Notes
Output Created	23-APR-2022 08:31:14
Comments	
Input	Data	E:\DATA_JOBS\HierarchicalRegression\impulse_data_A3 (3).sav
	Active Dataset	DataSet2
	Filter	<none>
	Weight	<none>
	Split File	<none>
	N of Rows in Working Data File	456
Syntax	CODEBOOK  id [s] sex [n] age [s] i1 [o] i2 [o] i3 [o] impulse [s] rses [s] des [s] i4 [o] i5 [o] i6
    [o] i7 [o] i8 [o] i9 [o] i10 [o] i11 [o] i12 [o] i13 [o] i14 [o]
  /VARINFO POSITION LABEL TYPE FORMAT MEASURE ROLE VALUELABELS MISSING ATTRIBUTES
  /OPTIONS VARORDER=VARLIST SORT=ASCENDING MAXCATS=200
  /STATISTICS COUNT PERCENT MEAN STDDEV QUARTILES.
Resources	Processor Time	00:00:00.02
	Elapsed Time	00:00:00.05


id
	Value
Standard Attributes	Position	1
	Label	Participant's ID
	Type	Numeric
	Format	F2
	Measurement	Scale
	Role	Input
N	Valid	456
	Missing	0
Central Tendency and Dispersion	Mean	228.50
	Standard Deviation	131.780
	Percentile 25	114.50
	Percentile 50	228.50
	Percentile 75	342.50


sex
	Value	Count	Percent
Standard Attributes	Position	2		
	Label	Biological sex		
	Type	Numeric		
	Format	F1		
	Measurement	Nominal		
	Role	Input		
Valid Values	1	Male	214	46.9%
	2	Female	242	53.1%


age
	Value
Standard Attributes	Position	3
	Label	Age
	Type	Numeric
	Format	F2
	Measurement	Scale
	Role	Input
N	Valid	456
	Missing	0
Central Tendency and Dispersion	Mean	44.90
	Standard Deviation	11.069
	Percentile 25	36.00
	Percentile 50	44.00
	Percentile 75	52.00


i1
	Value	Count	Percent
Standard Attributes	Position	4		
	Label	Item 1		
	Type	Numeric		
	Format	F1		
	Measurement	Ordinal		
	Role	Input		
Valid Values	1		17	3.7%
	2		51	11.2%
	3		47	10.3%
	4		197	43.2%
	5		144	31.6%


i2
	Value	Count	Percent
Standard Attributes	Position	5		
	Label	Item 2		
	Type	Numeric		
	Format	F1		
	Measurement	Ordinal		
	Role	Input		
Valid Values	1		112	24.6%
	2		116	25.4%
	3		71	15.6%
	4		109	23.9%
	5		48	10.5%


i3
	Value	Count	Percent
Standard Attributes	Position	6		
	Label	Item 3		
	Type	Numeric		
	Format	F1		
	Measurement	Ordinal		
	Role	Input		
Valid Values	1		18	3.9%
	2		46	10.1%
	3		54	11.8%
	4		206	45.2%
	5		132	28.9%


impulse
	Value
Standard Attributes	Position	18
	Label	Impulsiveness Scale
	Type	Numeric
	Format	F2
	Measurement	Scale
	Role	Input
N	Valid	456
	Missing	0
Central Tendency and Dispersion	Mean	29.50
	Standard Deviation	9.592
	Percentile 25	22.50
	Percentile 50	28.00
	Percentile 75	36.00


rses
	Value
Standard Attributes	Position	19
	Label	Rosenberg's Self-Esteem Scale
	Type	Numeric
	Format	F2
	Measurement	Scale
	Role	Input
N	Valid	456
	Missing	0
Central Tendency and Dispersion	Mean	14.48
	Standard Deviation	5.927
	Percentile 25	10.00
	Percentile 50	15.00
	Percentile 75	18.00


des
	Value
Standard Attributes	Position	20
	Label	Dispositional Envy Scale
	Type	Numeric
	Format	F2
	Measurement	Scale
	Role	Input
N	Valid	456
	Missing	0
Central Tendency and Dispersion	Mean	25.61
	Standard Deviation	6.308
	Percentile 25	20.00
	Percentile 50	25.00
	Percentile 75	31.00


i4
	Value	Count	Percent
Standard Attributes	Position	7		
	Label	Item 4		
	Type	Numeric		
	Format	F1		
	Measurement	Ordinal		
	Role	Input		
Valid Values	1		173	37.9%
	2		128	28.1%
	3		52	11.4%
	4		68	14.9%
	5		35	7.7%


i5
	Value	Count	Percent
Standard Attributes	Position	8		
	Label	Item 5		
	Type	Numeric		
	Format	F1		
	Measurement	Ordinal		
	Role	Input		
Valid Values	1		127	27.9%
	2		130	28.5%
	3		75	16.4%
	4		86	18.9%
	5		37	8.1%
	6		1	0.2%


i6
	Value	Count	Percent
Standard Attributes	Position	9		
	Label	Item 6		
	Type	Numeric		
	Format	F1		
	Measurement	Ordinal		
	Role	Input		
Valid Values	1		74	16.2%
	2		120	26.3%
	3		91	20.0%
	4		127	27.9%
	5		44	9.6%


i7
	Value	Count	Percent
Standard Attributes	Position	10		
	Label	Item 7		
	Type	Numeric		
	Format	F1		
	Measurement	Ordinal		
	Role	Input		
Valid Values	1		81	17.8%
	2		145	31.8%
	3		101	22.1%
	4		94	20.6%
	5		35	7.7%


i8
	Value	Count	Percent
Standard Attributes	Position	11		
	Label	Item 8		
	Type	Numeric		
	Format	F1		
	Measurement	Ordinal		
	Role	Input		
Valid Values	1		40	8.8%
	2		78	17.1%
	3		61	13.4%
	4		171	37.5%
	5		106	23.2%


i9
	Value	Count	Percent
Standard Attributes	Position	12		
	Label	Item 9		
	Type	Numeric		
	Format	F1		
	Measurement	Ordinal		
	Role	Input		
Valid Values	1		78	17.1%
	2		157	34.4%
	3		86	18.9%
	4		101	22.1%
	5		34	7.5%


i10
	Value	Count	Percent
Standard Attributes	Position	13		
	Label	Item 10		
	Type	Numeric		
	Format	F1		
	Measurement	Ordinal		
	Role	Input		
Valid Values	1		33	7.2%
	2		91	20.0%
	3		68	14.9%
	4		136	29.8%
	5		128	28.1%


i11
	Value	Count	Percent
Standard Attributes	Position	14		
	Label	Item 11		
	Type	Numeric		
	Format	F1		
	Measurement	Ordinal		
	Role	Input		
Valid Values	1		98	21.5%
	2		175	38.4%
	3		67	14.7%
	4		73	16.0%
	5		43	9.4%


i12
	Value	Count	Percent
Standard Attributes	Position	15		
	Label	Item 12		
	Type	Numeric		
	Format	F1		
	Measurement	Ordinal		
	Role	Input		
Valid Values	1		131	28.7%
	2		147	32.2%
	3		81	17.8%
	4		66	14.5%
	5		31	6.8%


i13
	Value	Count	Percent
Standard Attributes	Position	16		
	Label	Item 13		
	Type	Numeric		
	Format	F1		
	Measurement	Ordinal		
	Role	Input		
Valid Values	1		24	5.3%
	2		47	10.3%
	3		65	14.3%
	4		202	44.3%
	5		118	25.9%


i14
	Value	Count	Percent
Standard Attributes	Position	17		
	Label	Item 14		
	Type	Numeric		
	Format	F1		
	Measurement	Ordinal		
	Role	Input		
Valid Values	1		111	24.3%
	2		147	32.2%
	3		70	15.4%
	4		92	20.2%
	5		36	7.9%

STATS CANCORR SET1=age   SET2=impulse rses des
/OPTIONS  ROOTNAME="Correlation between Sex and the Subject Study Variables" COMPUTECVARS=NO
/PRINT PAIRWISECORR=YES LOADINGS=YES VARPROP=YES COEFFICIENTS=YES.




Correlations



Notes
Output Created	23-APR-2022 08:40:50
Comments	
Input	Data	E:\DATA_JOBS\HierarchicalRegression\impulse_data_A3 (3).sav
	Active Dataset	DataSet2
	Filter	<none>
	Weight	<none>
	Split File	<none>
	N of Rows in Working Data File	456
Missing Value Handling	Definition of Missing	User-defined missing values are treated as missing.
	Cases Used	Statistics are based on cases with no missing data for any variable used.
Syntax	CORRELATIONS age impulse rses des /MISSING=LISTWISE/PRINT=SIG
    /MATRIX OUT('C:/Users/97jos/AppData/Local/Temp/0.905080292397.sav').
Resources	Processor Time	00:00:00.03
	Elapsed Time	00:00:00.20
Files Saved	Matrix File	C:\Users\97jos\AppData\Local\Temp\0.905080292397.sav


Correlationsa
	Age	Impulsiveness Scale	Rosenberg's Self-Esteem Scale	
Age	Pearson Correlation	1	-.091	.111	
	Sig. (2-tailed)		.051	.018	
Impulsiveness Scale	Pearson Correlation	-.091	1	.329	
	Sig. (2-tailed)	.051		.000	
Rosenberg's Self-Esteem Scale	Pearson Correlation	.111	.329	1	
	Sig. (2-tailed)	.018	.000		
Dispositional Envy Scale	Pearson Correlation	-.061	.435	-.262	
	Sig. (2-tailed)	.193	.000	.000	



Canonical Correlations



Notes
Output Created	23-APR-2022 08:40:53
Comments	
Input	Data	E:\DATA_JOBS\HierarchicalRegression\impulse_data_A3 (3).sav
	Active Dataset	DataSet2
	Filter	<none>
	Weight	<none>
	Split File	<none>
Syntax	BEGIN PROGRAM '#
	'.
Resources	Processor Time	00:00:00.05
	Elapsed Time	00:00:00.11


[DataSet2] E:\DATA_JOBS\HierarchicalRegression\impulse_data_A3 (3).sav



Canonical Correlations Settings
	Values
Set 1 Variables	age
Set 2 Variables	impulse rses des
Centered Dataset	None
Scoring Syntax	None
Correlations Used for Scoring	1


Canonical Correlations
	Correlation	Eigenvalue	Wilks Statistic	F	Num D.F	Denom D.F.	Sig.
1	.183	.035	.966	5.233	3.000	452.000	.001

H0 for Wilks test is that the correlations in the current and following rows are zero


Set 1 Standardized Canonical Correlation Coefficients
Variable	1
age	1.000


Set 2 Standardized Canonical Correlation Coefficients
Variable	1
impulse	-1.000
rses	1.032
des	.371


Set 1 Unstandardized Canonical Correlation Coefficients
Variable	1
age	.090


Set 2 Unstandardized Canonical Correlation Coefficients
Variable	1
impulse	-.104
rses	.174
des	.059


Set 1 Canonical Loadings
Variable	1
age	1.000


Set 2 Canonical Loadings
Variable	1
impulse	-.499
rses	.606
des	-.334


Set 1 Cross Loadings
Variable	1
age	.183


Set 2 Cross Loadings
Variable	1
impulse	-.091
rses	.111
des	-.061


Proportion of Variance Explained
Canonical Variable	Set 1 by Self	Set 1 by Set 2	Set 2 by Self	Set 2 by Set 1
1	1.000	.034	.242	.008

CORRELATIONS
  /VARIABLES=sex impulse des rses
  /PRINT=TWOTAIL NOSIG
  /MISSING=PAIRWISE.




Correlations



Notes
Output Created	23-APR-2022 08:42:48
Comments	
Input	Data	E:\DATA_JOBS\HierarchicalRegression\impulse_data_A3 (3).sav
	Active Dataset	DataSet2
	Filter	<none>
	Weight	<none>
	Split File	<none>
	N of Rows in Working Data File	456
Missing Value Handling	Definition of Missing	User-defined missing values are treated as missing.
	Cases Used	Statistics for each pair of variables are based on all the cases with valid data for that pair.
Syntax	CORRELATIONS
  /VARIABLES=sex impulse des rses
  /PRINT=TWOTAIL NOSIG
  /MISSING=PAIRWISE.
Resources	Processor Time	00:00:00.02
	Elapsed Time	00:00:00.01


Correlations
	Biological sex	Impulsiveness Scale	Dispositional Envy Scale	
Biological sex	Pearson Correlation	1	-.130**	-.021	
	Sig. (2-tailed)		.005	.650	
	N	456	456	456	
Impulsiveness Scale	Pearson Correlation	-.130**	1	.435**	
	Sig. (2-tailed)	.005		.000	
	N	456	456	456	
Dispositional Envy Scale	Pearson Correlation	-.021	.435**	1	
	Sig. (2-tailed)	.650	.000		
	N	456	456	456	
Rosenberg's Self-Esteem Scale	Pearson Correlation	-.014	.329**	-.262**	
	Sig. (2-tailed)	.768	.000	.000	
	N	456	456	456	

NONPAR CORR
  /VARIABLES=sex impulse des rses
  /PRINT=BOTH TWOTAIL NOSIG
  /MISSING=PAIRWISE.




Nonparametric Correlations



Notes
Output Created	23-APR-2022 08:42:48
Comments	
Input	Data	E:\DATA_JOBS\HierarchicalRegression\impulse_data_A3 (3).sav
	Active Dataset	DataSet2
	Filter	<none>
	Weight	<none>
	Split File	<none>
	N of Rows in Working Data File	456
Missing Value Handling	Definition of Missing	User-defined missing values are treated as missing.
	Cases Used	Statistics for each pair of variables are based on all the cases with valid data for that pair.
Syntax	NONPAR CORR
  /VARIABLES=sex impulse des rses
  /PRINT=BOTH TWOTAIL NOSIG
  /MISSING=PAIRWISE.
Resources	Processor Time	00:00:00.02
	Elapsed Time	00:00:00.07
	Number of Cases Allowed	449389 casesa

a. Based on availability of workspace memory


Correlations
	Biological sex	Impulsiveness Scale		
Kendall's tau_b	Biological sex	Correlation Coefficient	1.000	-.104**		
		Sig. (2-tailed)	.	.008		
		N	456	456		
	Impulsiveness Scale	Correlation Coefficient	-.104**	1.000		
		Sig. (2-tailed)	.008	.		
		N	456	456		
	Dispositional Envy Scale	Correlation Coefficient	-.020	.301**		
		Sig. (2-tailed)	.612	.000		
		N	456	456		
	Rosenberg's Self-Esteem Scale	Correlation Coefficient	-.002	.224**		
		Sig. (2-tailed)	.959	.000		
		N	456	456		
Spearman's rho	Biological sex	Correlation Coefficient	1.000	-.125**		
		Sig. (2-tailed)	.	.007		
		N	456	456		
	Impulsiveness Scale	Correlation Coefficient	-.125**	1.000		
		Sig. (2-tailed)	.007	.		
		N	456	456		
	Dispositional Envy Scale	Correlation Coefficient	-.024	.420**		
		Sig. (2-tailed)	.613	.000		
		N	456	456		
	Rosenberg's Self-Esteem Scale	Correlation Coefficient	-.002	.312**		
		Sig. (2-tailed)	.960	.000		
		N	456	456		

FREQUENCIES VARIABLES=sex impulse rses des age
  /NTILES=4
  /NTILES=10
  /STATISTICS=STDDEV VARIANCE RANGE MINIMUM MAXIMUM SEMEAN MEAN MEDIAN MODE SUM SKEWNESS SESKEW
    KURTOSIS SEKURT
  /GROUPED=sex impulse rses des age
  /PIECHART PERCENT
  /ORDER=ANALYSIS.




Frequencies



Notes
Output Created	23-APR-2022 08:44:50
Comments	
Input	Data	E:\DATA_JOBS\HierarchicalRegression\impulse_data_A3 (3).sav
	Active Dataset	DataSet2
	Filter	<none>
	Weight	<none>
	Split File	<none>
	N of Rows in Working Data File	456
Missing Value Handling	Definition of Missing	User-defined missing values are treated as missing.
	Cases Used	Statistics are based on all cases with valid data.
Syntax	FREQUENCIES VARIABLES=sex impulse rses des age
  /NTILES=4
  /NTILES=10
  /STATISTICS=STDDEV VARIANCE RANGE MINIMUM MAXIMUM SEMEAN MEAN MEDIAN MODE SUM SKEWNESS SESKEW
    KURTOSIS SEKURT
  /GROUPED=sex impulse rses des age
  /PIECHART PERCENT
  /ORDER=ANALYSIS.
Resources	Processor Time	00:00:03.31
	Elapsed Time	00:00:02.23


Statistics
	Biological sex	Impulsiveness Scale	Rosenberg's Self-Esteem Scale	Dispositional Envy Scale	Age
N	Valid	456	456	456	456	456
	Missing	0	0	0	0	0
Mean	1.53	29.50	14.48	25.61	44.90
Std. Error of Mean	.023	.449	.278	.295	.518
Median	1.53a	28.26a	14.64a	25.51a	45.60a
Mode	2	26	15	28	52
Std. Deviation	.500	9.592	5.927	6.308	11.069
Variance	.250	92.000	35.134	39.786	122.533
Skewness	-.123	.440	.014	-.029	-.195
Std. Error of Skewness	.114	.114	.114	.114	.114
Kurtosis	-1.994	-.316	-.686	-.356	-.807
Std. Error of Kurtosis	.228	.228	.228	.228	.228
Range	1	44	28	32	47
Minimum	1	12	1	9	19
Maximum	2	56	29	41	66
Sum	698	13451	6602	11678	20475
Percentiles	10	.b,c	17.44c	6.41c	16.90c	29.21c
	20	.	21.34	8.91	19.60	34.54
	25	1.03	22.47	10.10	20.94	36.56
	30	1.13	23.58	10.73	22.98	38.21
	40	1.33	26.04	13.10	24.12	42.13
	50	1.53	28.26	14.64	25.51	45.60
	60	1.73	31.01	16.15	27.32	49.28
	70	1.93	34.05	17.51	29.00	51.71
	75	.	35.74	18.32	30.73	53.30
	80	.	37.65	20.39	31.54	55.12
	90	.	43.16	22.77	32.98	59.62

a. Calculated from grouped data.
b. The lower bound of the first interval or the upper bound of the last interval is not known. Some percentiles are undefined.
c. Percentiles are calculated from grouped data.



Frequency Table



Biological sex
	Frequency	Percent	Valid Percent	Cumulative Percent
Valid	Male	214	46.9	46.9	46.9
	Female	242	53.1	53.1	100.0
	Total	456	100.0	100.0	


Impulsiveness Scale
	Frequency	Percent	Valid Percent	Cumulative Percent
Valid	12	8	1.8	1.8	1.8
	13	5	1.1	1.1	2.9
	14	3	.7	.7	3.5
	15	9	2.0	2.0	5.5
	16	11	2.4	2.4	7.9
	17	9	2.0	2.0	9.9
	18	14	3.1	3.1	12.9
	19	9	2.0	2.0	14.9
	20	9	2.0	2.0	16.9
	21	16	3.5	3.5	20.4
	22	21	4.6	4.6	25.0
	23	24	5.3	5.3	30.3
	24	13	2.9	2.9	33.1
	25	17	3.7	3.7	36.8
	26	27	5.9	5.9	42.8
	27	16	3.5	3.5	46.3
	28	25	5.5	5.5	51.8
	29	10	2.2	2.2	53.9
	30	17	3.7	3.7	57.7
	31	21	4.6	4.6	62.3
	32	11	2.4	2.4	64.7
	33	16	3.5	3.5	68.2
	34	15	3.3	3.3	71.5
	35	12	2.6	2.6	74.1
	36	15	3.3	3.3	77.4
	37	10	2.2	2.2	79.6
	38	11	2.4	2.4	82.0
	39	8	1.8	1.8	83.8
	40	9	2.0	2.0	85.7
	41	10	2.2	2.2	87.9
	42	5	1.1	1.1	89.0
	43	7	1.5	1.5	90.6
	44	4	.9	.9	91.4
	45	8	1.8	1.8	93.2
	46	4	.9	.9	94.1
	47	3	.7	.7	94.7
	48	7	1.5	1.5	96.3
	49	5	1.1	1.1	97.4
	51	2	.4	.4	97.8
	52	3	.7	.7	98.5
	53	4	.9	.9	99.3
	55	2	.4	.4	99.8
	56	1	.2	.2	100.0
	Total	456	100.0	100.0	


Rosenberg's Self-Esteem Scale
	Frequency	Percent	Valid Percent	Cumulative Percent
Valid	1	1	.2	.2	.2
	2	6	1.3	1.3	1.5
	3	9	2.0	2.0	3.5
	6	44	9.6	9.6	13.2
	8	30	6.6	6.6	19.7
	10	41	9.0	9.0	28.7
	11	31	6.8	6.8	35.5
	13	35	7.7	7.7	43.2
	15	83	18.2	18.2	61.4
	17	39	8.6	8.6	70.0
	18	39	8.6	8.6	78.5
	21	27	5.9	5.9	84.4
	22	27	5.9	5.9	90.4
	24	35	7.7	7.7	98.0
	25	4	.9	.9	98.9
	28	4	.9	.9	99.8
	29	1	.2	.2	100.0
	Total	456	100.0	100.0	


Dispositional Envy Scale
	Frequency	Percent	Valid Percent	Cumulative Percent
Valid	9	1	.2	.2	.2
	11	5	1.1	1.1	1.3
	12	6	1.3	1.3	2.6
	15	9	2.0	2.0	4.6
	16	16	3.5	3.5	8.1
	17	21	4.6	4.6	12.7
	19	30	6.6	6.6	19.3
	20	31	6.8	6.8	26.1
	23	36	7.9	7.9	34.0
	24	45	9.9	9.9	43.9
	25	35	7.7	7.7	51.5
	27	47	10.3	10.3	61.8
	28	48	10.5	10.5	72.4
	31	31	6.8	6.8	79.2
	32	40	8.8	8.8	87.9
	33	20	4.4	4.4	92.3
	35	11	2.4	2.4	94.7
	37	10	2.2	2.2	96.9
	39	10	2.2	2.2	99.1
	40	2	.4	.4	99.6
	41	2	.4	.4	100.0
	Total	456	100.0	100.0	


Age
	Frequency	Percent	Valid Percent	Cumulative Percent
Valid	19	1	.2	.2	.2
	22	8	1.8	1.8	2.0
	24	15	3.3	3.3	5.3
	27	16	3.5	3.5	8.8
	30	21	4.6	4.6	13.4
	33	29	6.4	6.4	19.7
	36	32	7.0	7.0	26.8
	38	25	5.5	5.5	32.2
	41	40	8.8	8.8	41.0
	44	42	9.2	9.2	50.2
	47	33	7.2	7.2	57.5
	50	41	9.0	9.0	66.4
	52	45	9.9	9.9	76.3
	55	31	6.8	6.8	83.1
	58	32	7.0	7.0	90.1
	61	25	5.5	5.5	95.6
	64	18	3.9	3.9	99.6
	66	2	.4	.4	100.0
	Total	456	100.0	100.0	



Pie Chart


 


 


 


 


 


FREQUENCIES VARIABLES=i1 i2 i3 i4 i5 i6 i7 i8 i9 i10 i11 i12 i13 i14
  /NTILES=4
  /NTILES=10
  /STATISTICS=STDDEV VARIANCE RANGE MINIMUM MAXIMUM SEMEAN MEAN MEDIAN MODE SUM SKEWNESS SESKEW
    KURTOSIS SEKURT
  /GROUPED=i1 i2 i3 i4 i5 i6 i7 i8 i9 i10 i11 i12 i13 i14
  /PIECHART PERCENT
  /ORDER=ANALYSIS.




Frequencies



Notes
Output Created	23-APR-2022 08:49:05
Comments	
Input	Data	E:\DATA_JOBS\HierarchicalRegression\impulse_data_A3 (3).sav
	Active Dataset	DataSet2
	Filter	<none>
	Weight	<none>
	Split File	<none>
	N of Rows in Working Data File	456
Missing Value Handling	Definition of Missing	User-defined missing values are treated as missing.
	Cases Used	Statistics are based on all cases with valid data.
Syntax	FREQUENCIES VARIABLES=i1 i2 i3 i4 i5 i6 i7 i8 i9 i10 i11 i12 i13 i14
  /NTILES=4
  /NTILES=10
  /STATISTICS=STDDEV VARIANCE RANGE MINIMUM MAXIMUM SEMEAN MEAN MEDIAN MODE SUM SKEWNESS SESKEW
    KURTOSIS SEKURT
  /GROUPED=i1 i2 i3 i4 i5 i6 i7 i8 i9 i10 i11 i12 i13 i14
  /PIECHART PERCENT
  /ORDER=ANALYSIS.
Resources	Processor Time	00:00:04.06
	Elapsed Time	00:00:02.57


Statistics
	Item 1	Item 2	Item 3	Item 4	Item 5	Item 6								
N	Valid	456	456	456	456	456	456								
	Missing	0	0	0	0	0	0								
Mean	3.88	2.70	3.85	2.26	2.52	2.88								
Std. Error of Mean	.051	.063	.050	.061	.061	.059								
Median	4.09a	2.62a	4.04a	1.94a	2.35a	2.89a								
Mode	4	2	4	1	2	4								
Std. Deviation	1.091	1.347	1.071	1.310	1.304	1.252								
Variance	1.189	1.813	1.147	1.715	1.701	1.567								
Skewness	-.970	.204	-.972	.731	.438	.018								
Std. Error of Skewness	.114	.114	.114	.114	.114	.114								
Kurtosis	.216	-1.249	.345	-.720	-.973	-1.128								
Std. Error of Kurtosis	.228	.228	.228	.228	.228	.228								
Range	4	4	4	4	5	4								
Minimum	1	1	1	1	1	1								
Maximum	5	5	5	5	6	5								
Sum	1768	1233	1756	1032	1147	1315								
Percentiles	10	2.06b	.b,c	2.09b	.b,c	.b,c	1.09b								
	20	2.99	1.31	3.00	1.03	1.22	1.56								
	25	3.18	1.51	3.18	1.18	1.39	1.79								
	30	3.37	1.71	3.35	1.33	1.57	2.03								
	40	3.75	2.13	3.70	1.64	1.93	2.46								
	50	4.09	2.62	4.04	1.94	2.35	2.89								
	60	4.35	3.11	4.31	2.41	2.80	3.31								
	70	4.62	3.62	4.58	2.91	3.31	3.73								
	75	4.75	3.87	4.72	3.25	3.59	3.94								
	80	4.89	4.14	4.85	3.63	3.87	4.19								
	90	.	4.72	.	4.45	4.58	4.72								



Frequency Table



Item 1
	Frequency	Percent	Valid Percent	Cumulative Percent
Valid	1	17	3.7	3.7	3.7
	2	51	11.2	11.2	14.9
	3	47	10.3	10.3	25.2
	4	197	43.2	43.2	68.4
	5	144	31.6	31.6	100.0
	Total	456	100.0	100.0	


Item 2
	Frequency	Percent	Valid Percent	Cumulative Percent
Valid	1	112	24.6	24.6	24.6
	2	116	25.4	25.4	50.0
	3	71	15.6	15.6	65.6
	4	109	23.9	23.9	89.5
	5	48	10.5	10.5	100.0
	Total	456	100.0	100.0	


Item 3
	Frequency	Percent	Valid Percent	Cumulative Percent
Valid	1	18	3.9	3.9	3.9
	2	46	10.1	10.1	14.0
	3	54	11.8	11.8	25.9
	4	206	45.2	45.2	71.1
	5	132	28.9	28.9	100.0
	Total	456	100.0	100.0	


Item 4
	Frequency	Percent	Valid Percent	Cumulative Percent
Valid	1	173	37.9	37.9	37.9
	2	128	28.1	28.1	66.0
	3	52	11.4	11.4	77.4
	4	68	14.9	14.9	92.3
	5	35	7.7	7.7	100.0
	Total	456	100.0	100.0	


Item 5
	Frequency	Percent	Valid Percent	Cumulative Percent
Valid	1	127	27.9	27.9	27.9
	2	130	28.5	28.5	56.4
	3	75	16.4	16.4	72.8
	4	86	18.9	18.9	91.7
	5	37	8.1	8.1	99.8
	6	1	.2	.2	100.0
	Total	456	100.0	100.0	


Item 6
	Frequency	Percent	Valid Percent	Cumulative Percent
Valid	1	74	16.2	16.2	16.2
	2	120	26.3	26.3	42.5
	3	91	20.0	20.0	62.5
	4	127	27.9	27.9	90.4
	5	44	9.6	9.6	100.0
	Total	456	100.0	100.0	


Item 7
	Frequency	Percent	Valid Percent	Cumulative Percent
Valid	1	81	17.8	17.8	17.8
	2	145	31.8	31.8	49.6
	3	101	22.1	22.1	71.7
	4	94	20.6	20.6	92.3
	5	35	7.7	7.7	100.0
	Total	456	100.0	100.0	


Item 8
	Frequency	Percent	Valid Percent	Cumulative Percent
Valid	1	40	8.8	8.8	8.8
	2	78	17.1	17.1	25.9
	3	61	13.4	13.4	39.3
	4	171	37.5	37.5	76.8
	5	106	23.2	23.2	100.0
	Total	456	100.0	100.0	


Item 9
	Frequency	Percent	Valid Percent	Cumulative Percent
Valid	1	78	17.1	17.1	17.1
	2	157	34.4	34.4	51.5
	3	86	18.9	18.9	70.4
	4	101	22.1	22.1	92.5
	5	34	7.5	7.5	100.0
	Total	456	100.0	100.0	


Item 10
	Frequency	Percent	Valid Percent	Cumulative Percent
Valid	1	33	7.2	7.2	7.2
	2	91	20.0	20.0	27.2
	3	68	14.9	14.9	42.1
	4	136	29.8	29.8	71.9
	5	128	28.1	28.1	100.0
	Total	456	100.0	100.0	


Item 11
	Frequency	Percent	Valid Percent	Cumulative Percent
Valid	1	98	21.5	21.5	21.5
	2	175	38.4	38.4	59.9
	3	67	14.7	14.7	74.6
	4	73	16.0	16.0	90.6
	5	43	9.4	9.4	100.0
	Total	456	100.0	100.0	


Item 12
	Frequency	Percent	Valid Percent	Cumulative Percent
Valid	1	131	28.7	28.7	28.7
	2	147	32.2	32.2	61.0
	3	81	17.8	17.8	78.7
	4	66	14.5	14.5	93.2
	5	31	6.8	6.8	100.0
	Total	456	100.0	100.0	


Item 13
	Frequency	Percent	Valid Percent	Cumulative Percent
Valid	1	24	5.3	5.3	5.3
	2	47	10.3	10.3	15.6
	3	65	14.3	14.3	29.8
	4	202	44.3	44.3	74.1
	5	118	25.9	25.9	100.0
	Total	456	100.0	100.0	


Item 14
	Frequency	Percent	Valid Percent	Cumulative Percent
Valid	1	111	24.3	24.3	24.3
	2	147	32.2	32.2	56.6
	3	70	15.4	15.4	71.9
	4	92	20.2	20.2	92.1
	5	36	7.9	7.9	100.0
	Total	456	100.0	100.0	



Pie Chart


 


 


 


 


 


 


 


 


 


 


 


 


 


 


*Automatic Linear Modeling.
LINEAR
  /FIELDS TARGET=impulse INPUTS=age i1 i2 i3 i4 i5 i6 i7 i8 i9 i10 i11 i12 i13 i14 ANALYSIS_WEIGHT=sex
  /BUILD_OPTIONS OBJECTIVE=STANDARD USE_AUTO_DATA_PREPARATION=TRUE CONFIDENCE_LEVEL=95 MODEL_SELECTION=FORWARDSTEPWISE CRITERIA_FORWARD_STEPWISE=AICC REPLICATE_RESULTS=TRUE SEED=54752075
  /ENSEMBLES COMBINING_RULE_CONTINUOUS=MEAN COMPONENT_MODELS_N=10.




Automatic Linear Modeling



Notes
Output Created	23-APR-2022 09:12:59
Comments	
Input	Data	E:\DATA_JOBS\HierarchicalRegression\impulse_data_A3 (3).sav
	Active Dataset	DataSet2
	Filter	<none>
	Weight	<none>
	Split File	<none>
	N of Rows in Working Data File	456
Syntax	LINEAR
  /FIELDS TARGET=impulse INPUTS=age i1 i2 i3 i4 i5 i6 i7 i8 i9 i10 i11 i12 i13 i14 ANALYSIS_WEIGHT=sex
  /BUILD_OPTIONS OBJECTIVE=STANDARD USE_AUTO_DATA_PREPARATION=TRUE CONFIDENCE_LEVEL=95 MODEL_SELECTION=FORWARDSTEPWISE CRITERIA_FORWARD_STEPWISE=AICC REPLICATE_RESULTS=TRUE SEED=54752075
  /ENSEMBLES COMBINING_RULE_CONTINUOUS=MEAN COMPONENT_MODELS_N=10.
Resources	Processor Time	00:00:01.58
	Elapsed Time	00:00:02.34


Case Processing Summary
	N	Percent
Included	456	100.0%
Excluded	0	0.0%
Total	456	100.0%

 

null : null

 


*Automatic Linear Modeling.
LINEAR
  /FIELDS TARGET=rses INPUTS=age i1 i2 i3 i4 i5 i6 i7 i8 i9 i10 i11 i12 i13 i14 ANALYSIS_WEIGHT=sex
  /BUILD_OPTIONS OBJECTIVE=STANDARD USE_AUTO_DATA_PREPARATION=TRUE CONFIDENCE_LEVEL=95 MODEL_SELECTION=FORWARDSTEPWISE CRITERIA_FORWARD_STEPWISE=AICC REPLICATE_RESULTS=TRUE SEED=54752075
  /ENSEMBLES COMBINING_RULE_CONTINUOUS=MEAN COMPONENT_MODELS_N=10.




Automatic Linear Modeling



Notes
Output Created	23-APR-2022 10:03:00
Comments	
Input	Data	E:\DATA_JOBS\HierarchicalRegression\impulse_data_A3 (3).sav
	Active Dataset	DataSet2
	Filter	<none>
	Weight	<none>
	Split File	<none>
	N of Rows in Working Data File	456
Syntax	LINEAR
  /FIELDS TARGET=rses INPUTS=age i1 i2 i3 i4 i5 i6 i7 i8 i9 i10 i11 i12 i13 i14 ANALYSIS_WEIGHT=sex
  /BUILD_OPTIONS OBJECTIVE=STANDARD USE_AUTO_DATA_PREPARATION=TRUE CONFIDENCE_LEVEL=95 MODEL_SELECTION=FORWARDSTEPWISE CRITERIA_FORWARD_STEPWISE=AICC REPLICATE_RESULTS=TRUE SEED=54752075
  /ENSEMBLES COMBINING_RULE_CONTINUOUS=MEAN COMPONENT_MODELS_N=10.
Resources	Processor Time	00:00:00.45
	Elapsed Time	00:00:00.99


Case Processing Summary
	N	Percent
Included	456	100.0%
Excluded	0	0.0%
Total	456	100.0%

 

null : null

 


*Automatic Linear Modeling.
LINEAR
  /FIELDS TARGET=rses INPUTS=age i1 i2 i3 i4 i5 i6 i7 i8 i9 i10 i11 i12 i13 i14 ANALYSIS_WEIGHT=sex
  /BUILD_OPTIONS OBJECTIVE=STANDARD USE_AUTO_DATA_PREPARATION=TRUE CONFIDENCE_LEVEL=95 MODEL_SELECTION=FORWARDSTEPWISE CRITERIA_FORWARD_STEPWISE=AICC REPLICATE_RESULTS=TRUE SEED=54752075
  /ENSEMBLES COMBINING_RULE_CONTINUOUS=MEAN COMPONENT_MODELS_N=10.




Automatic Linear Modeling



Notes
Output Created	23-APR-2022 10:03:45
Comments	
Input	Data	E:\DATA_JOBS\HierarchicalRegression\impulse_data_A3 (3).sav
	Active Dataset	DataSet2
	Filter	<none>
	Weight	<none>
	Split File	<none>
	N of Rows in Working Data File	456
Syntax	LINEAR
  /FIELDS TARGET=rses INPUTS=age i1 i2 i3 i4 i5 i6 i7 i8 i9 i10 i11 i12 i13 i14 ANALYSIS_WEIGHT=sex
  /BUILD_OPTIONS OBJECTIVE=STANDARD USE_AUTO_DATA_PREPARATION=TRUE CONFIDENCE_LEVEL=95 MODEL_SELECTION=FORWARDSTEPWISE CRITERIA_FORWARD_STEPWISE=AICC REPLICATE_RESULTS=TRUE SEED=54752075
  /ENSEMBLES COMBINING_RULE_CONTINUOUS=MEAN COMPONENT_MODELS_N=10.
Resources	Processor Time	00:00:00.41
	Elapsed Time	00:00:00.42


Case Processing Summary
	N	Percent
Included	456	100.0%
Excluded	0	0.0%
Total	456	100.0%

 

null : null

 


*Automatic Linear Modeling.
LINEAR
  /FIELDS TARGET=des INPUTS=age i1 i2 i3 i4 i5 i6 i7 i8 i9 i10 i11 i12 i13 i14 ANALYSIS_WEIGHT=sex
  /BUILD_OPTIONS OBJECTIVE=STANDARD USE_AUTO_DATA_PREPARATION=TRUE CONFIDENCE_LEVEL=95 MODEL_SELECTION=FORWARDSTEPWISE CRITERIA_FORWARD_STEPWISE=AICC REPLICATE_RESULTS=TRUE SEED=54752075
  /ENSEMBLES COMBINING_RULE_CONTINUOUS=MEAN COMPONENT_MODELS_N=10.




Automatic Linear Modeling



Notes
Output Created	23-APR-2022 10:04:35
Comments	
Input	Data	E:\DATA_JOBS\HierarchicalRegression\impulse_data_A3 (3).sav
	Active Dataset	DataSet2
	Filter	<none>
	Weight	<none>
	Split File	<none>
	N of Rows in Working Data File	456
Syntax	LINEAR
  /FIELDS TARGET=des INPUTS=age i1 i2 i3 i4 i5 i6 i7 i8 i9 i10 i11 i12 i13 i14 ANALYSIS_WEIGHT=sex
  /BUILD_OPTIONS OBJECTIVE=STANDARD USE_AUTO_DATA_PREPARATION=TRUE CONFIDENCE_LEVEL=95 MODEL_SELECTION=FORWARDSTEPWISE CRITERIA_FORWARD_STEPWISE=AICC REPLICATE_RESULTS=TRUE SEED=54752075
  /ENSEMBLES COMBINING_RULE_CONTINUOUS=MEAN COMPONENT_MODELS_N=10.
Resources	Processor Time	00:00:00.33
	Elapsed Time	00:00:00.41


Case Processing Summary
	N	Percent
Included	456	100.0%
Excluded	0	0.0%
Total	456	100.0%

 

null : null

 


*Automatic Linear Modeling.
LINEAR
  /FIELDS TARGET=impulse INPUTS=i1 i2 i3 i4 i5 i6 i7 i8 i9 i10 i11 i12 i13 i14 sex ANALYSIS_WEIGHT=age
  /BUILD_OPTIONS OBJECTIVE=STANDARD USE_AUTO_DATA_PREPARATION=TRUE CONFIDENCE_LEVEL=95 MODEL_SELECTION=FORWARDSTEPWISE CRITERIA_FORWARD_STEPWISE=AICC REPLICATE_RESULTS=TRUE SEED=54752075
  /ENSEMBLES COMBINING_RULE_CONTINUOUS=MEAN COMPONENT_MODELS_N=10.




Automatic Linear Modeling



Notes
Output Created	23-APR-2022 10:32:52
Comments	
Input	Data	E:\DATA_JOBS\HierarchicalRegression\impulse_data_A3 (3).sav
	Active Dataset	DataSet2
	Filter	<none>
	Weight	<none>
	Split File	<none>
	N of Rows in Working Data File	456
Syntax	LINEAR
  /FIELDS TARGET=impulse INPUTS=i1 i2 i3 i4 i5 i6 i7 i8 i9 i10 i11 i12 i13 i14 sex ANALYSIS_WEIGHT=age
  /BUILD_OPTIONS OBJECTIVE=STANDARD USE_AUTO_DATA_PREPARATION=TRUE CONFIDENCE_LEVEL=95 MODEL_SELECTION=FORWARDSTEPWISE CRITERIA_FORWARD_STEPWISE=AICC REPLICATE_RESULTS=TRUE SEED=54752075
  /ENSEMBLES COMBINING_RULE_CONTINUOUS=MEAN COMPONENT_MODELS_N=10.
Resources	Processor Time	00:00:00.59
	Elapsed Time	00:00:02.08


Case Processing Summary
	N	Percent
Included	456	100.0%
Excluded	0	0.0%
Total	456	100.0%

 

null : null

 


*Automatic Linear Modeling.
LINEAR
  /FIELDS TARGET=rses INPUTS=i1 i2 i3 i4 i5 i6 i7 i8 i9 i10 i11 i12 i13 i14 sex ANALYSIS_WEIGHT=age
  /BUILD_OPTIONS OBJECTIVE=STANDARD USE_AUTO_DATA_PREPARATION=TRUE CONFIDENCE_LEVEL=95 MODEL_SELECTION=FORWARDSTEPWISE CRITERIA_FORWARD_STEPWISE=AICC REPLICATE_RESULTS=TRUE SEED=54752075
  /ENSEMBLES COMBINING_RULE_CONTINUOUS=MEAN COMPONENT_MODELS_N=10.




Automatic Linear Modeling



Notes
Output Created	23-APR-2022 10:33:45
Comments	
Input	Data	E:\DATA_JOBS\HierarchicalRegression\impulse_data_A3 (3).sav
	Active Dataset	DataSet2
	Filter	<none>
	Weight	<none>
	Split File	<none>
	N of Rows in Working Data File	456
Syntax	LINEAR
  /FIELDS TARGET=rses INPUTS=i1 i2 i3 i4 i5 i6 i7 i8 i9 i10 i11 i12 i13 i14 sex ANALYSIS_WEIGHT=age
  /BUILD_OPTIONS OBJECTIVE=STANDARD USE_AUTO_DATA_PREPARATION=TRUE CONFIDENCE_LEVEL=95 MODEL_SELECTION=FORWARDSTEPWISE CRITERIA_FORWARD_STEPWISE=AICC REPLICATE_RESULTS=TRUE SEED=54752075
  /ENSEMBLES COMBINING_RULE_CONTINUOUS=MEAN COMPONENT_MODELS_N=10.
Resources	Processor Time	00:00:00.31
	Elapsed Time	00:00:00.67


Case Processing Summary
	N	Percent
Included	456	100.0%
Excluded	0	0.0%
Total	456	100.0%

 

null : null

 


*Automatic Linear Modeling.
LINEAR
  /FIELDS TARGET=des INPUTS=i1 i2 i3 i4 i5 i6 i7 i8 i9 i10 i11 i12 i13 i14 sex ANALYSIS_WEIGHT=age
  /BUILD_OPTIONS OBJECTIVE=STANDARD USE_AUTO_DATA_PREPARATION=TRUE CONFIDENCE_LEVEL=95 MODEL_SELECTION=FORWARDSTEPWISE CRITERIA_FORWARD_STEPWISE=AICC REPLICATE_RESULTS=TRUE SEED=54752075
  /ENSEMBLES COMBINING_RULE_CONTINUOUS=MEAN COMPONENT_MODELS_N=10.




Automatic Linear Modeling



Notes
Output Created	23-APR-2022 10:34:17
Comments	
Input	Data	E:\DATA_JOBS\HierarchicalRegression\impulse_data_A3 (3).sav
	Active Dataset	DataSet2
	Filter	<none>
	Weight	<none>
	Split File	<none>
	N of Rows in Working Data File	456
Syntax	LINEAR
  /FIELDS TARGET=des INPUTS=i1 i2 i3 i4 i5 i6 i7 i8 i9 i10 i11 i12 i13 i14 sex ANALYSIS_WEIGHT=age
  /BUILD_OPTIONS OBJECTIVE=STANDARD USE_AUTO_DATA_PREPARATION=TRUE CONFIDENCE_LEVEL=95 MODEL_SELECTION=FORWARDSTEPWISE CRITERIA_FORWARD_STEPWISE=AICC REPLICATE_RESULTS=TRUE SEED=54752075
  /ENSEMBLES COMBINING_RULE_CONTINUOUS=MEAN COMPONENT_MODELS_N=10.
Resources	Processor Time	00:00:00.37
	Elapsed Time	00:00:00.42


Case Processing Summary
	N	Percent
Included	456	100.0%
Excluded	0	0.0%
Total	456	100.0%

 

null : null

 


QUICK CLUSTER i1 i2 i3 i4 i5 i6 i7 i8 i9 i10 i11 i12 i13 i14
  /MISSING=LISTWISE
  /CRITERIA=CLUSTER(2) MXITER(10) CONVERGE(0)
  /METHOD=KMEANS(UPDATE)
  /PRINT ID(sex) INITIAL.




Quick Cluster



Notes
Output Created	23-APR-2022 10:40:14
Comments	
Input	Data	E:\DATA_JOBS\HierarchicalRegression\impulse_data_A3 (3).sav
	Active Dataset	DataSet2
	Filter	<none>
	Weight	<none>
	Split File	<none>
	N of Rows in Working Data File	456
Missing Value Handling	Definition of Missing	User-defined missing values are treated as missing.
	Cases Used	Statistics are based on cases with no missing values for any clustering variable used.
Syntax	QUICK CLUSTER i1 i2 i3 i4 i5 i6 i7 i8 i9 i10 i11 i12 i13 i14
  /MISSING=LISTWISE
  /CRITERIA=CLUSTER(2) MXITER(10) CONVERGE(0)
  /METHOD=KMEANS(UPDATE)
  /PRINT ID(sex) INITIAL.
Resources	Processor Time	00:00:00.09
	Elapsed Time	00:00:00.18
	Workspace Required	2112 bytes


Initial Cluster Centers
	Cluster
	1	2
Item 1	1	5
Item 2	1	4
Item 3	2	5
Item 4	5	1
Item 5	1	4
Item 6	5	3
Item 7	1	5
Item 8	2	5
Item 9	5	1
Item 10	1	5
Item 11	5	1
Item 12	4	1
Item 13	1	5
Item 14	4	1


Iteration Historya
Iteration	Change in Cluster Centers
	1	2
1	5.881	4.560
2	.740	.522
3	.172	.127
4	.001	.001
5	3.204E-6	2.477E-6
6	1.381E-8	1.096E-8
7	5.953E-11	4.851E-11
8	2.572E-13	2.116E-13
9	4.441E-16	3.053E-15
10	.000	.000

a. Convergence achieved due to no or small change in cluster centers. The maximum absolute coordinate change for any center is .000. The current iteration is 10. The minimum distance between initial centers is 13.038.


Final Cluster Centers
	Cluster
	1	2
Item 1	3	4
Item 2	3	2
Item 3	3	4
Item 4	3	2
Item 5	3	2
Item 6	4	2
Item 7	3	2
Item 8	3	4
Item 9	3	2
Item 10	3	4
Item 11	3	2
Item 12	3	2
Item 13	3	4
Item 14	3	2


Number of Cases in each Cluster
Cluster	1	216.000
	2	240.000
Valid	456.000
Missing	.000

* Spectral Analysis.
TSET  PRINT=DEFAULT.
SPECTRA
  /VARIABLES=sex age i1 i2 i3 i4 i5 i6 i7 i8 i9 i10 i11 i12 i13 i14 id impulse rses des
  /WINDOW=HAMMING(5)
  /CENTER
  /CROSS
  /PLOT=P S K CS QS PH A G BY FREQUENCY.




Spectral Analysis



Notes
Output Created	23-APR-2022 10:49:26
Comments	
Input	Data	E:\DATA_JOBS\HierarchicalRegression\impulse_data_A3 (3).sav
	Active Dataset	DataSet2
	Filter	<none>
	Weight	<none>
	Split File	<none>
	N of Rows in Working Data File	456
Missing Value Handling	Definition of Missing	User-defined missing values are treated as missing.
	Cases Used	No missing value is allowed anywhere in any series.
Syntax	SPECTRA
  /VARIABLES=sex age i1 i2 i3 i4 i5 i6 i7 i8 i9 i10 i11 i12 i13 i14 id impulse rses des
  /WINDOW=HAMMING(5)
  /CENTER
  /CROSS
  /PLOT=P S K CS QS PH A G BY FREQUENCY.
Resources	Processor Time	00:00:29.44
	Elapsed Time	00:00:28.24
Use	From	First observation
	To	Last observation
Time Series Settings (TSET)	Amount of Output	PRINT = DEFAULT
	Saving New Variables	NEWVAR = CURRENT
	Maximum Number of Lags in Autocorrelation or Partial Autocorrelation Plots	MXAUTO = 16
	Maximum Number of Lags Per Cross-Correlation Plots	MXCROSS = 7
	Maximum Number of New Variables Generated Per Procedure	MXNEWVAR = 60
	Maximum Number of New Cases Per Procedure	MXPREDICT = 1000
	Treatment of User-Missing Values	MISSING = EXCLUDE
	Confidence Interval Percentage Value	CIN = 95
	Tolerance for Entering Variables in Regression Equations	TOLER = .0001
	Maximum Iterative Parameter Change	CNVERGE = .001
	Method of Calculating Std. Errors for Autocorrelations	ACFSE = IND
	Length of Seasonal Period	Unspecified
	Variable Whose Values Label Observations in Plots	Unspecified
	Equations Include	CONSTANT


Model Description
Model Name	MOD_1
Analysis Type	Univariate and Bivariate
Independent Series	Biological sex
Dependent Series	1	Age
	2	Item 1
	3	Item 2
	4	Item 3
	5	Item 4
	6	Item 5
	7	Item 6
	8	Item 7
	9	Item 8
	10	Item 9
	11	Item 10
	12	Item 11
	13	Item 12
	14	Item 13
	15	Item 14
	16	Participant's ID
	17	Impulsiveness Scale
	18	Rosenberg's Self-Esteem Scale
	19	Dispositional Envy Scale
Range of Values	Reduced by Centering at Zero
Periodogram Smoothing	Spectral Window	Tukey-Hamming
	Window Span	5
	Weight Value	W(-2)	2.239
		W(-1)	2.240
		W(0)	2.240
		W(1)	2.240
		W(2)	2.239

Applying the model specifications from MOD_1



Biological sex


 


 




Age


 


 




age with sex


 


 


 


 


 


 




Item 1


 


 




i1 with sex


 


 


 


 


 


 




Item 2


 


 




i2 with sex


 


 


 


 


 


 




Item 3


 


 




i3 with sex


 


 


 


 


 


 




Item 4


 


 




i4 with sex


 


 


 


 


 


 




Item 5


 


 




i5 with sex


 


 


 


 


 


 




Item 6


 


 




i6 with sex


 


 


 


 


 


 




Item 7


 


 




i7 with sex


 


 


 


 


 


 




Item 8


 


 




i8 with sex


 


 


 


 


 


 




Item 9


 


 




i9 with sex


 


 


 


 


 


 




Item 10


 


 




i10 with sex


 


 


 


 


 


 




Item 11


 


 




i11 with sex


 


 


 


 


 


 




Item 12


 


 




i12 with sex


 


 


 


 


 


 




Item 13


 


 




i13 with sex


 


 


 


 


 


 




Item 14


 


 




i14 with sex


 


 


 


 


 


 




Participant's ID


 


 




id with sex


 


 


 


 


 


 




Impulsiveness Scale


 


 




impulse with sex


 


 


 


 


 


 




Rosenberg's Self-Esteem Scale


 


 




rses with sex


 


 


 


 


 


 




Dispositional Envy Scale


 


 




des with sex


 


 


 


 


 


 


* Spectral Analysis.
TSET  PRINT=DEFAULT.
SPECTRA
  /VARIABLES=age i1 i2 i3 i4 i5 i6 i7 i8 i9 i10 i11 i12 i13 i14 id impulse rses des
  /WINDOW=HAMMING(5)
  /CENTER
  /CROSS
  /PLOT=P S K CS QS PH A G BY FREQUENCY.




Spectral Analysis



Notes
Output Created	23-APR-2022 10:51:02
Comments	
Input	Data	E:\DATA_JOBS\HierarchicalRegression\impulse_data_A3 (3).sav
	Active Dataset	DataSet2
	Filter	<none>
	Weight	<none>
	Split File	<none>
	N of Rows in Working Data File	456
Missing Value Handling	Definition of Missing	User-defined missing values are treated as missing.
	Cases Used	No missing value is allowed anywhere in any series.
Syntax	SPECTRA
  /VARIABLES=age i1 i2 i3 i4 i5 i6 i7 i8 i9 i10 i11 i12 i13 i14 id impulse rses des
  /WINDOW=HAMMING(5)
  /CENTER
  /CROSS
  /PLOT=P S K CS QS PH A G BY FREQUENCY.
Resources	Processor Time	00:00:21.89
	Elapsed Time	00:00:21.73
Use	From	First observation
	To	Last observation
Time Series Settings (TSET)	Amount of Output	PRINT = DEFAULT
	Saving New Variables	NEWVAR = CURRENT
	Maximum Number of Lags in Autocorrelation or Partial Autocorrelation Plots	MXAUTO = 16
	Maximum Number of Lags Per Cross-Correlation Plots	MXCROSS = 7
	Maximum Number of New Variables Generated Per Procedure	MXNEWVAR = 60
	Maximum Number of New Cases Per Procedure	MXPREDICT = 1000
	Treatment of User-Missing Values	MISSING = EXCLUDE
	Confidence Interval Percentage Value	CIN = 95
	Tolerance for Entering Variables in Regression Equations	TOLER = .0001
	Maximum Iterative Parameter Change	CNVERGE = .001
	Method of Calculating Std. Errors for Autocorrelations	ACFSE = IND
	Length of Seasonal Period	Unspecified
	Variable Whose Values Label Observations in Plots	Unspecified
	Equations Include	CONSTANT


Model Description
Model Name	MOD_2
Analysis Type	Univariate and Bivariate
Independent Series	Age
Dependent Series	1	Item 1
	2	Item 2
	3	Item 3
	4	Item 4
	5	Item 5
	6	Item 6
	7	Item 7
	8	Item 8
	9	Item 9
	10	Item 10
	11	Item 11
	12	Item 12
	13	Item 13
	14	Item 14
	15	Participant's ID
	16	Impulsiveness Scale
	17	Rosenberg's Self-Esteem Scale
	18	Dispositional Envy Scale
Range of Values	Reduced by Centering at Zero
Periodogram Smoothing	Spectral Window	Tukey-Hamming
	Window Span	5
	Weight Value	W(-2)	2.239
		W(-1)	2.240
		W(0)	2.240
		W(1)	2.240
		W(2)	2.239

Applying the model specifications from MOD_2



Age


 


 




Item 1


 


 




i1 with age


 


 


 


 


 


 




Item 2


 


 




i2 with age


 


 


 


 


 


 




Item 3


 


 




i3 with age


 


 


 


 


 


 




Item 4


 


 




i4 with age


 


 


 


 


 


 




Item 5


 


 




i5 with age


 


 


 


 


 


 




Item 6


 


 




i6 with age


 


 


 


 


 


 




Item 7


 


 




i7 with age


 


 


 


 


 


 




Item 8


 


 




i8 with age


 


 


 


 


 


 




Item 9


 


 




i9 with age


 


 


 


 


 


 




Item 10


 


 




i10 with age


 


 


 


 


 


 




Item 11


 


 




i11 with age


 


 


 


 


 


 




Item 12


 


 




i12 with age


 


 


 


 


 


 




Item 13


 


 




i13 with age


 


 


 


 


 


 




Item 14


 


 




i14 with age


 


 


 


 


 


 




Participant's ID


 


 




id with age


 


 


 


 


 


 




Impulsiveness Scale


 


 




impulse with age


 


 


 


 


 


 




Rosenberg's Self-Esteem Scale


 


 




rses with age


 


 


 


 


 


 




Dispositional Envy Scale


 


 




des with age


 


 


 


 


 


 



