## Artificial Intelligence in Medical Sciences: Only with Transparent and Representative AI Training Data

Artificial Intelligence (AI) is increasingly being applied in healthcare, with extensive research exploring its potential. Current applications include analyzing medical images and laboratory data to support diagnostics, surgery, and treatment. AI can also be used to identify risk factors and personalize treatment plans, promising a revolution in healthcare. However, it is crucial to ensure that AI training data is transparent and representative, reflecting the diversity of the population.

### Bias in training data
When an AI algorithm is trained primarily on data from a specific population group, it can produce skewed outcomes and lower diagnostic accuracy for other groups, a phenomenon known as racial bias (Kapur, 2021; Obermeyer & Emanuel, 2016). A clear example comes from research in dermatology. Numerous studies have examined the use of AI in dermatological diagnostics. However, many of these publications fail to report the (ethnic) composition of their study populations. If an algorithm is trained predominantly on individuals with lighter skin tones, diagnostic accuracy may decrease for those with darker skin tones (Buolamwini & Gebru, 2018; Phillips et al., 2019). 
Similarly, bone density varies significantly across ethnic groups. Studies show that Asian and white populations generally differ in bone density compared to Afro-Caribbean and African-American populations (Leslie, 2012). Such differences can influence clinical decisions regarding orthopedic procedures, such as hip or knee replacements.
Moreover, there are subtle anatomical differences between men and women, and they often present disease symptoms differently. When certain groups are underrepresented in algorithm training, the risk increases that these individuals will receive lower-quality care because the AI system does not adequately account for them (Buolamwini & Gebru, 2018). Providing inferior care to specific groups conflicts with the fundamental principle of equality and equal treatment.

### Black-box
AI models often consist of multiple processing layers with numerous parameters (Buolamwini & Gebru, 2018), functioning as a black box that makes it difficult to understand how the algorithm arrives at its decisions. While methods exist to increase explainability, such as indicating which features (e.g., blood values or imaging results) contributed to a decision, these approaches can also introduce confirmation bias among clinicians (Phillips et al., 2019).
Because the use of AI algorithms challenges the principle of transparency, it is essential that representative training data is used during development. It must be clear which data the algorithm was trained on and how patient subgroups are proportioned. A healthy dataset should be both transparent and generalizable.

### Appropriate ratios
Extensive research into AI algorithms is essential, but in small-scale studies it can be challenging to include diverse subgroups, as achieving a representative study population often requires considerable time and effort. This makes it difficult to conduct such research sporadically or without thorough preparation. Nonetheless, failing to actively consider representativeness risks sending the wrong signal to society, where inclusivity and the right of every individual to receive proper healthcare and equal treatment are highly valued.
This raises the question: which criteria determine whether differences should be made between individuals or groups at all? It is impossible to endlessly differentiate between groups of people, however, at the very least, the foundation of a “healthy” dataset lies in good representation of age, sex, and ethnicity. When researching psychosocial conditions, it may be logical to include proportional data from different subcultures or socioeconomic groups.

### Sensitivity
A drawback of a dataset that integrates all subgroups is that diagnostics for certain subgroups may become less sensitive. For example, if a dataset is trained on both men and women, certain abnormalities may be detected less accurately in women than if the dataset had been trained solely on female data. Therefore, if, for specific reasons, only a particular subgroup is included in the dataset, this must be explicitly described in the research methodology. When the algorithm is applied in practice, its use should be limited to that specific subgroup.


### Conclusion
Artificial Intelligence will increasingly be applied in medical sciences. It is therefore crucial to carefully consider the ethical aspects of this technology. Research into diagnostic applications of AI offers many opportunities but also carries risks, such as the emergence of racial bias. This creates the danger that certain groups may receive lower-quality care because the AI algorithm does not adequately represent them. This forms an ethical dilemma, as it conflicts with the principle of equality and equal treatment. Transparency regarding the (ethnic) diversity of AI training datasets is essential to ensure they are both healthy and generalizable. If only specific subgroups are included in a dataset, this should be explicitly documented in the methodology, and the algorithm must be applied only to the corresponding subgroup. When determining which criteria should guide subgroup distinctions, at minimum age, sex, and ethnicity must be considered. In certain cases, distinctions based on subcultures or socioeconomic status may also be relevant.

### References

1. Kapur, S. (2021, June 1). Reducing racial bias in AI models for clinical use requires a top-down intervention. Nature Machine Intelligence, 3(6), 460. https://doi.org/10.1038/s42256-021-00362-7

2. Obermeyer, Z., & Emanuel, E. J. (2016). Predicting the Future — Big Data, Machine Learning, and Clinical Medicine. New England Journal of Medicine, 375(13), 1216–1219. https://doi.org/10.1056/NEJMp1606181

3. Phillips, M., Marsden, H., Jaffe, W., Matin, R. N., Wali, G. N., Greenhalgh, J., McGrath, E., James, R., Ladoyanni, E., Bewley, A., Argenziano, G., & Palamaras, I. (2019). Assessment of Accuracy of an Artificial Intelligence Algorithm to Detect Melanoma in Images of Skin Lesions. JAMA Network Open, 2(10), e1913436. https://doi.org/10.1001/jamanetworkopen.2019.13436

4. Buolamwini, J., & Gebru, T. (2018). Gender Shades: Intersectional Accuracy Disparities in Commercial Gender Classification. Proceedings of the 1st Conference on Fairness, Accountability and Transparency, Proceedings of Machine Learning Research. https://proceedings.mlr.press/v81/buolamwini18a.html

5. Leslie, W. D. (2012). Ethnic Differences in Bone Mass—Clinical Implications. The Journal of Clinical Endocrinology & Metabolism, 97(12), 4329–4340. https://doi.org/10.1210/jc.2012-2863

### About
Date of writing: 12-09-2023
