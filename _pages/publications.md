---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

## Publications

### Books
P. Santikellur and R. S. Chakraborty, “Deep Learning for Computational Problems in Hardware Security: Modeling Attacks on Strong Physically Unclonable Function Circuits”, Vol. 1052. Springer Nature, 2022. doi: https://doi.org/10.1007/978-981-19-4017-0

## Journal Papers  

P. Santikellur, M. Buddhanoy, S. Sakib, B. Ray and R.S Chakraborty, ”A Shared Page-Aware Machine Learning Assisted Method for Predicting and Improving Multi-Level Cell NAND Flash Memory Life Expectancy”, Microelectronics Reliability, 140, p.114867. doi: 10.1016/j.microrel.2022.114867

P. Santikellur and R. S. Chakraborty, ”Correlation Integral based In-trinsic Dimension: a Deep Learning Assisted Empirical Metric to Esti-mate the Robustness of Physically Unclonable Functions to ModelingAttacks,” in IEEE Transactions on Computer-Aided Design of IntegratedCircuits and Systems, vol. 41, no. 10, pp. 3216-3227, Oct. 2022, doi:10.1109/TCAD.2021.3129112.

S. Chattaopadhyay, P. Santikellur, R. S. Chakraborty, J. Mathew and M. Ottavi, ”A Conditionally Chaotic Physically Unclonable Function De-sign Framework with High Reliability”, in ACM Transactions on Design Automation of Electronic Systems, 26, 6, Article 41 (November 2021), pp.1-24.doi:10.1145/3460004  

P. Santikellur and R. S. Chakraborty, ”A Computationally Efficient Ten-sor Regression Network based Modeling Attack on XOR Arbiter PUFand its Variants” in IEEE Transactions on Computer-Aided Design of Inte-grated Circuits and Systems., vol. 40, no. 6, pp. 1197-1206, June 2021, doi:10.1109/TCAD.2020.3032624.  

V. Govindan, R. S. Chakraborty, P. Santikellur., A.K Chaudhary, ”A Hardware Trojan Attack on FPGA based Cryptographic Key Genera-tion: Impact and Detection”, Journal of Hardware and Systems Security(Springer), vol. 2, no. 3, pp. 225-239, Sep. 2018. doi: 10.1007/s41635-018-0042-5  

## Book Chapters  

P. Santikellur, R. S. Chakraborty, and J. Mathew, ”Hardware Securityin the Context of Internet of Things: Challenges and Opportunities.”Internet of Things and Secure Smart Environments: Successes and Pitfalls,2020, p.64.  

P. Santikellur, R. S. Chakraborty, S. Bhunia, (2022). Hardware IP Protec-tion Using Register Transfer Level Locking and Obfuscation of Controland Data Flow. In: Katkoori, S., Islam, S.A. (eds) Behavioral Synthesisfor Hardware Security. Springer, Cham. https://doi.org/10.1007/978-3-030-78841-44  

## Conference Papers  

P. Santikellur, R. Mukherjee, and R. S. Chakraborty. ”APUF-BNN: AnAutomated Framework for Efficient Combinational Logic Based Imple-mentation of Arbiter PUF through Binarized Neural Network”. In Pro-ceedings of the 2021 on Great Lakes Symposium on VLSI (GLSVLSI ’21). As-sociation for Computing Machinery, New York, NY, USA, 89–94. (BestPaper Nominated)  

P. Santikellur, Lakshya, S. R. Prakash and R. S. Chakraborty, ”A Computationally Efficient Tensor Regression Network based Modeling Attackon XOR Arbiter PUF”, IEEE Asian Hardware Oriented Security and TrustSymposium (AsianHOST), 2019, pp. 1-6.
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
