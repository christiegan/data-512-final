# data-512-final
Final Project

### Proposal
I plan on examining mental health of tech workers around the world, of all genders, and all ages. Based on age, gender, and location, how does mental health affect those who work in the tech industry differently? We know that the tech industry is very fast-paced; but I want to see how it affects mental health for different demographics.

### Goals:
To determine which factors significantly affect mental health, and to inform tech employers of which demographics to be mindful of. We hope that tech companies can cater and adapt their mental health care support to these groups who may feel marginalized or otherwise unsupported in the industry. This helps with employee retention, keeps morale up and generally creates a more efficient and positive atmosphere.

### Data Source:
Data origin: [Kaggle](https://www.kaggle.com/osmi/mental-health-in-tech-survey)
Data collected by: [Open Sourcing Mental Illness](https://osmihelp.org/)

The license is CC BY-SA 4.0.
Link to license: https://creativecommons.org/licenses/by-sa/4.0/
Public dataset

### Final CSV Details
Raw Data (referenced in Kaggle):

- Timestamp

- Age

- Gender

- Country

- state: If you live in the United States, which state or territory do you live in?

- self_employed: Are you self-employed?

- family_history: Do you have a family history of mental illness?

- treatment: Have you sought treatment for a mental health condition?

- work_interfere: If you have a mental health condition, do you feel that it interferes with your work?

- no_employees: How many employees does your company or organization have?

- remote_work: Do you work remotely (outside of an office) at least 50% of the time?

- tech_company: Is your employer primarily a tech company/organization?

- benefits: Does your employer provide mental health benefits?

- care_options: Do you know the options for mental health care your employer provides?

- wellness_program: Has your employer ever discussed mental health as part of an employee wellness program?

- seek_help: Does your employer provide resources to learn more about mental health issues and how to seek help?

- anonymity: Is your anonymity protected if you choose to take advantage of mental health or substance abuse treatment resources?

- leave: How easy is it for you to take medical leave for a mental health condition?

- mentalhealthconsequence: Do you think that discussing a mental health issue with your employer would have negative consequences?

- physhealthconsequence: Do you think that discussing a physical health issue with your employer would have negative consequences?

- coworkers: Would you be willing to discuss a mental health issue with your coworkers?

- supervisor: Would you be willing to discuss a mental health issue with your direct supervisor(s)?

- mentalhealthinterview: Would you bring up a mental health issue with a potential employer in an interview?

- physhealthinterview: Would you bring up a physical health issue with a potential employer in an interview?

- mentalvsphysical: Do you feel that your employer takes mental health as seriously as physical health?

- obs_consequence: Have you heard of or observed negative consequences for coworkers with mental health conditions in your workplace?

- comments: Any additional notes or comments

### Special Considerations:
- I refer to mental health score and work_interfere_xx interchangeably 
- I alter the original work_interfere column to work_interfere_num and work_interfere_binary for easier statistical analysis. The mapping is as follows:
- work_interfere_num
    - Never -> 0
    - Rarely -> 1
    - Sometimes -> 2
    - Often -> 3
- work_interfere_binary
    - Never -> 0
    - Rarely -> 1
    - Sometimes -> 1
    - Often -> 1
- The number of respondents across the demographics are unequal, i.e., much more males responded to this survey than females.