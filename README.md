# Iterative-Health-NLP-Project
Automating IBD Classification of Inflammatory Bowel Disease Patients based on Disease Severity using Clinical Notes

## Summary:

This project aims to leverage machine learning algorithms and natural language processing (NLP) to automate the identification of patients with active Inflammatory Bowel Disease (IBD). Currently, the process of identifying such patients is entirely manual, but a Massachusetts-based AI company is using videos and electronic health record (EHR) data to develop more efficient and accurate methods.

The company's approach involves analyzing images, videos, and text-based data, including exam notes and image metadata, to surface patients with active IBD. By identifying keyword-centric patterns among patients with IBD, the team has found specific keywords with a high positive predictive value for IBD patients, such as "ileitis." However, the challenge lies in distinguishing between different disease severities, as these keywords may also appear in patients with various conditions.

The team is exploring the possibility of developing NLP algorithms to automate the identification process. They aim to identify multi-word sequences associated with active IBD, allowing for a more consistent and less biased approach compared to manual querying of healthcare provider data.
Additional Information: MUST READ !!!

    * What is Crohn’s Disease? Crohn's disease is a chronic inflammatory bowel disease (IBD) that can affect any part of the gastrointestinal (GI) tract, leading to inflammation, ulceration, and thickening of the bowel wall. Common symptoms include abdominal pain, diarrhea, weight loss, and more.

    * What is Endoscopy? Endoscopy is a medical procedure that uses a flexible tube equipped with a camera to examine the inside of the GI tract.

    * What is a Simple Endo Score? The Simple Endoscopic Score for Crohn's Disease (SES-CD) is a tool used to assess the severity of Crohn's disease based on endoscopic findings. It evaluates aspects such as ulceration severity, affected bowel extent, ulcer size, and presence of narrowing or strictures.

    * What does ileitis mean? Ileitis refers to inflammation of the ileum, the last section of the small intestine. In the context of Crohn's disease, ileitis is a common form characterized by chronic inflammation and ulceration in the gastrointestinal tract.

## Methodology:

The proposed methodology involves using unstructured textual processing of Electronic Health Record (EHR) data to identify multi-word sequences associated with active IBD. By developing NLP algorithms, certain text patterns can reliably predict active IBD, automating the patient surfacing process for clinical trial referral, which is currently a manual process.

The NLP algorithms will analyze unstructured data like text notes and image comments to extract meaningful information. Machine learning algorithms will then be employed to identify patterns associated with active disease. The resulting models can automatically identify and flag exam notes and image comments containing relevant information for further review by healthcare professionals.
Current Manual Process:

    * ICD Filtering for IBD: The current approach involves using International Classification of Diseases (ICD) codes (K50 & K51) to identify patients with Inflammatory Bowel Disease (IBD) from electronic health records (EHRs).

    * ICD Filtering for I/E: ICD filtering for hospital inpatient (I) and outpatient (E) encounters is used to identify specific conditions or procedures associated with hospital admissions or outpatient visits.

    * Keyword Queries: NLP algorithms are used to analyze text notes and image comments, identifying keywords and phrases indicating the presence of active disease.

    * Internal image review: Expert physicians review images for signs of clearly active disease.

    * GI(Gastro-Intestinal) image review: Images are reviewed for disease severity and assigned threshold scores (350+ classified as active by GIs).

## Requirements:

The project requires the use of NLP and machine learning techniques to develop models for detecting active IBD from expert physician's inputs. Vectorization of words through neural networks, such as word2vec, doc2vec, and fasttext, will help find associations between words and reduce internal biases. The vectorized text can be used as input to predict the presence of active IBD on an exam using machine learning techniques.

## Deliverables:

    A report showcasing the methodology, descriptive statistics on word frequencies, and a results section presenting individual words and multi-word sequences associated with exams showing active IBD.

    The code (Python/R) used for the analysis.

## Data:

No Access

Please note that this readme file is an overview of the project and its objectives. For a comprehensive understanding, refer to the project documentation and associated code.
