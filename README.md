# ER-Injuries
NEISS Dataset (2017) Overview
This dataset comes from the National Electronic Injury Surveillance System (NEISS), maintained by the Consumer Product Safety Commission. NEISS is a long-term study that records all accidents reported in a representative sample of hospitals across the United States. Each record in this dataset includes details of an accident and a short narrative describing how it occurred.

Why NEISS?
The NEISS dataset is particularly interesting because it involves real-world accident scenarios that many users may relate to, providing a compelling basis for analysis. The data also includes a narrative for each entry, offering unique insights into the circumstances of each accident.

Focus on 2017 Data
For the purpose of this project, we are focusing exclusively on data collected in 2017. This subset is around 10 MB, making it small enough to manage easily and store in version control, like Git.

Note: The data for this chapter was extracted specifically for manageable exploration. More sophisticated data loading techniques will be covered in later sections of the book.

Additional Information
For more details about the NEISS dataset, you can explore the official GitHub repository where you can find further documentation and resources.

Each row in the NEISS dataset represents a single recorded accident, with the following 10 variables:

trmt_date: The date the person visited the hospital for treatment (not necessarily the accident date).
age: Age of the person involved in the accident.
sex: Gender of the individual.
race: Race of the individual.
body_part: The body part affected by the injury (e.g., ankle, ear).
location: The place where the accident occurred (e.g., home, school).
diag: The primary diagnosis of the injury (e.g., fracture, laceration).
prod_code: The code for the primary product associated with the injury.
weight: A statistical weight estimating the number of similar injuries across the US if scaled up to the population level.
narrative: A brief description of how the accident occurred.
