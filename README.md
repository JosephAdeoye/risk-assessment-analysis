# Risk Assessment Analysis

Here is a little background story of the company we would be conducting our risk assessment on as provided by **PwC**;

*Boldi AG is a family-owned business in Switzerland with around 90 employees. They are a premium component supplier for the chemical industry, they have 4 people in IT and hire external IT consultants now and then.*

*Last night the news had a story about a competitor who was hit by a severe ransomware attack. A wake-up call for Boldi AG: their last information risk analysis was conducted in 2014. Management has decided to ask top consultancies to pitch their cybersecurity services. You are working with your project lead on location at Boldi to learn as much as possible about the company. First, it is critical to establish a common understanding of information risk at Boldi AG. This means learning about the company and its culture.*

- What is their risk tolerance?

- How willing are they to accept risk?

- How do they handle changes in processes and systems?

## Here is the task

1. To learn more about Boldi AG and its culture, you first need to determine who you should talk to at Boldi AG and what the content of these interviews should be. How does your agenda differ based on the audience, e.g. management vs. engineers? Stefan is currently in a meeting, leave him a voicemail (no longer than 1.5 minutes).

2. Now you are prepared to conduct an information risk impact assessment. In the meantime, you discover that Boldi AG files on paper and the company’s cloud-based information systems are inconsistent in format and hard to use for analysis. Plus, there are no controls over who in the company can access these files. 

Does any of this present an information security concern? Please explain your answer in the slide deck. Think of this through the prism of confidentiality, integrity, and availability (CIA), and add slides to your started presentation.

3. After you know enough about Boldi AG, decide what type of risk assessment would be best, a quantitative risk assessment or a qualitative risk assessment. Then explain the difference between quantitative and qualitative assessments. What do you rely on to be able to perform a quantitative assessment? Which method could be more adapted for information security risk assessments? 

# Below Is How I Carried Out Each Task
## Task 1

This task requires me to leave a voicemail for my project manager, Stefan, detailing whom I would need to talk to at Boldi AG, as well as what the content of the interviews should be to determine the company’s culture. And also how the agenda differs based on the audience (managers vs. engineers). So, below is a voicemail I would drop for Stefan that explains how I would go about this:

https://github.com/JosephAdeoye/risk-assessment-analysis/assets/66190309/769d3204-970c-4385-95d0-d84695873bb7

##Task 2 & Task 3

The video below combines answers to tasks 2 & 3. In the slide show, I explained the risk that comes with Boldi AG’s files being on paper, and the company’s cloud-based information systems being inconsistent. And how risky it is that there are no controls over who in the company can access these files. I also distinguish between Qualitative and Quantitative Risks as well as which of these Risk Assessment methods is optimal for Boldi AG given their background story. Please watch the slide show below:

https://github.com/JosephAdeoye/risk-assessment-analysis/assets/66190309/10785cc1-6c5a-447b-a2e9-06575f1b69d9

While completing these tasks, I learned extensively about Qualitative and Quantitative Risk Assessments and Risk Modeling.

# What is Qualitative Risk Assessment?

Qualitative risk assessment is a subjective method that relies on expert judgment and qualitative data to assess and prioritize risks. It doesn't involve precise numerical values but rather uses descriptive terms such as **"low," "medium," or "high"** to categorize and prioritize risks.

## Key features of Qualitative Risk Assessment

1. **Subjective**: It relies on the expertise and judgment of cybersecurity professionals risk analysts, or subject matter experts to evaluate and interpret risks. Although, it is important to note that subjectivity can introduce a degree of bias into the assessment process. Different experts may perceive and prioritize risks differently based on their experiences and perspectives.

2. **Scalability**: Qualitative risk assessment is very scalable, making it suitable for quickly assessing a large number of risks. It can help organizations prioritize which risks need further, more detailed analysis through quantitative methods. This scalability is valuable when dealing with numerous potential risks in a cybersecurity context.

3. **Low Resource Requirement**: In comparison to quantitative risk assessment, the qualitative approach generally requires fewer resources. It doesn't demand extensive data collection or in-depth statistical analysis. This makes it more accessible and cost-effective for organizations with limited resources.


# What is Quantitative Risk Assessment?

Quantitative risk assessment involves the use of numerical values and mathematical models to measure and quantify cybersecurity risks. It aims to provide a more objective and precise assessment of risks by assigning specific values to various risk factors.

## Key features of Quantitative Risk Assessment

1. **Objective and Data-Driven**: One of the primary features of quantitative risk assessment is its objectivity. It relies on concrete data and mathematical models rather than subjective judgments. This objectivity helps in minimizing biases and providing a more accurate representation of the risks an organization faces.

2. **Resource Intensive**: Qualitative Risk Assessment is very much resource-intensive. Gathering accurate data, conducting risk assessments, and building and maintaining risk models can require substantial time, effort, and financial investment. However, the benefits of this approach can outweigh the costs when it comes to making critical security decisions.

3. **Numerical Representation**: In Quantitative Risk Assessment, risks are represented using numerical metrics. Commonly used metrics include probabilities, impact values, financial losses, and exposure factors. These metrics allow for precise quantification of risks, making it easier to compare and prioritize them based on their potential impact.

4. **Risk Modeling**: To perform quantitative risk assessment, organizations often use risk models. These models take into account various variables, such as threat likelihood, vulnerability severity, and asset value, to calculate the expected risk level. Common models include the **Annualized Loss Expectancy (ALE) and the Single Loss Expectancy (SLE)**.

**Risk Modeling Scenario (Annualized Loss Expectancy)**: Boldi AG operates an online retail platform that stores customer information, including names, addresses, and credit card details. They want to quantitatively assess the risk of a data breach.

**Asset Value (AV)**: The customer database is a critical asset for Boldi AG. In this case, let's say its estimated value is $2 million because it contains sensitive customer data vital to its operations.

**Exposure Factor (EF)**: EF represents the percentage of asset value that could be lost in the event of a breach. Let's assume that a data breach might result in a 60% loss of the asset value, taking into account potential costs such as legal fees, regulatory fines, customer compensation, and reputation damage. Therefore, EF is 0.60 (or 60%).

**Annualized Rate of Occurrence (ARO)**: ARO estimates how often a particular threat or event is likely to occur in a year. Let's assume that, based on historical data and threat intelligence, the ARO for data breaches of this type is 0.05, which means there's a 5% chance of a breach occurring in a given year.

To calculate **Annualized Loss Expectancy (ALE) = AV x EF x ARO**

In our scenario, that would be **$2,000,000 * 0.6 * 0.05 = $60,000.**

Therefore, the Annualized Loss Expectancy for the risk of a data breach for Boldi AG is **$60,000** per year. This means, on average, they can expect to lose **$60,000** annually due to potential data breaches.

By using risk modelling and ALE calculations, organizations like Boldi AG can prioritize security investments, implement preventive measures, and develop incident response plans to mitigate the financial impact of cybersecurity risks.

**Single Loss Expectancy (SLO)**: Single Loss Expectancy represents the estimated financial loss that would occur if a specific event or threat were to materialize.

Pulling the same information we used in calculating our ALE, we are simply going to omit the ARO since we are only interested in calculating the estimated loss for a Single occurrence.

To calculate **Single Loss Expectancy = AV * EF**.

**SLE = $2,000,000 * 0.6 = $1,200,000**.

Therefore, the **Single Loss Expectancy** for the risk of a single data breach occurrence is **$1,200,000**.

In summary, qualitative risk assessments give us a quick, expert-driven way to identify and prioritize risks, while quantitative assessments provide precise calculations of potential losses and probabilities.

When we delve into the quantitative angle of risk assessment, **Single Loss Expectancy (SLE)** helps us understand the loss from a single incident, while **Annualized Loss Expectancy (ALE)** combines SLE with the likelihood of that incident happening in a year. Ideally, ALE is lower than SLE, showing that we've factored in the chances of the risk occurring.

Together, these methods help organizations make smart choices to protect their assets and data in a world full of risks and opportunities.

View the task here: https://bit.ly/3riMU7G
