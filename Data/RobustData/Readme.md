
# There are 4 files
1. matchedFirmsHYRatios.csv for balanced sample of for HY Study[1]
2. matchedFirmsHYRatios1toN.csv for imbalanced sample of for HY Study[1]
3. matchedFirmsLiangRatios.csv for balanced sample of for Liang Study[2]
4. matchedFirmsLiangRatios1toN.csv for imbalanced sample of for Liang Study[2]
-------------------------------------
# Variables/features of two prior studies
1. Header for Liang Study[1]:
   - Flag	ID	Type	year	TA	Z1	Z2	Z3	Z4	Z5	V1	V2	V3	V4	V5	V6	V7	V8	V9	V10	V11	V12	V13	V14	V15	V16	V17	V18	V19	V20	V21	V22	V23	V24	V25	V26	V27	V28	V29	V30	V31	V32	V33	V34	V35	V36	V37	V38	V39	V40	V41	V42	V43	V44	V45	V46	V47	V48	V49	V50	V51	V52	V53	V54	V55	V56	V57	V58	V59	V60	V61	V62	V63	V64	V65	V66	V67	V68	V69	V70	V71	V72	V73	V74	V75	V76	V77	V78	V79	V80	V81	V83	V84	V85	V86	V87	V88	V89	V90	V91	V92	V93	V94	V95

2. Header for HY Study[2]:
   - Flag	ID	Type	year	TA	Z1	Z2	Z3	Z4	Z5	V1	V2	V3	V4	V5	V6	V7	V8	V9	V10	V11	V12	V13	V14	V15	V16

The list of two prior studies:
- [1] D. Liang, C.-C. Lu, C.-F. Tsai, and G.-A. Shih, “Financial ratios and corporate governance indicators in bankruptcy prediction: A comprehensive study,” Eur. J. Oper. Res., vol. 252, no. 2, pp. 561–572, 2016.
- [2] Y. P. Huang and M. F. Yen, “A new perspective of performance comparison among machine learning algorithms for financial distress prediction,” Appl. Soft Comput. J., vol. 83, p. 105663, 2019.
-------------------------------------
# Convert each .csv file to .mat file
First, read the .csv file then save it into .mat file.
1. matchedFirmsHYRatios = csvread("matchedFirmsHYRatios.csv")
2. save("matchedFirmsHYRatios.mat","matchedFirmsHYRatios")
