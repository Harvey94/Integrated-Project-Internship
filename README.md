# Integrated-Project-Internship

In the ever-changing world of insurance, staying ahead means knowing customers well, understanding risks, and keeping up with new trends. Insurance companies use data to make customers happier, manage risks better, and run smoothly.

This project wants to use fancy math to learn from two big sets of data. The first set has lots of info about policies, like who has them, what they cover, and what accidents happen. The second set adds more details about policy stuff, like changes in coverage or money paid out for losses.

By integrating and analyzing these datasets, our objective is to achieve several key goals:

Customer Segmentation and Profiling: We'll look at who our customers are, what they do, and what they like about their policies. This helps us group them in smart ways so we can offer them better products.

Risk Assessment and Mitigation: We'll dig into things like how long someone has had a policy, how old their car is, and how bad accidents are. This helps us see where there might be big risks and stop problems before they happen.

Fraud Detection and Prevention: With the inclusion of fraud-reported indicators and additional policy event details, we aim to develop robust fraud detection models. By leveraging advanced analytics and machine learning techniques, we endeavor to identify suspicious patterns and anomalies indicative of fraudulent behavior, thereby safeguarding the integrity of our operations and protecting our customers' interests.

Optimization of Operational Efficiency: By analyzing policy bind dates, incident timelines, and claim processing metrics, we seek to streamline our operational processes and enhance efficiency across the insurance lifecycle. Through data-driven insights, we aim to identify bottlenecks, optimize resource allocation, and improve overall operational performance.

Enhanced Customer Experience: Ultimately, our overarching goal is to enhance the overall customer experience by leveraging data-driven insights to anticipate and fulfill customer needs effectively. By understanding customer preferences, mitigating risks, and optimizing service delivery, we aim to foster long-term relationships built on trust, transparency, and reliability.

The dataset used in this Power BI project contains the following columns:
months_as_customer: Number of months the person has been a customer with the insurance company,
age: Age of the insured person,
policy_number: Unique identifier for each insurance policy,
policy_bind_date: Date when the policy was bound,
policy_state: State in which the policy was issued,
policy_csl: Coverage limit of the policy in the form of combined single limits,
policy_deductable: Deductible amount specified in the policy,
policy_annual_premium: Annual premium amount for the policy,
umbrella_limit: Coverage limit provided by an umbrella policy,
insured_zip: ZIP code of the insured person,
insured_sex: Gender of the insured person,
insured_education_level: Education level of the insured person,
insured_occupation: Occupation of the insured person,
insured_hobbies: Hobbies of the insured person,
insured_relationship: Relationship of the insured person with the policyholder,
capital-gains: Capital gains associated with the incident,
capital-loss: Capital losses associated with the incident,
incident_date: Date of the incident,
incident_type: Type of incident (e.g., single vehicle collision, multi-vehicle collision),
collision_type: Type of collision in the incident,
incident_severity: Severity of the incident,
authorities_contacted: Authorities contacted after the incident,
incident_state: State in which the incident occurred,
incident_city: City in which the incident occurred,
incident_location: Location of the incident,
incident_hour_of_the_day: Hour of the day when the incident occurred,
number_of_vehicles_involved: Number of vehicles involved in the incident,
property_damage: Whether property damage occurred during the incident,
bodily_injuries: Number of bodily injuries in the incident,
witnesses: Number of witnesses present during the incident,
police_report_available: Whether a police report is available for the incident,
total_claim_amount: Total claim amount associated with the incident,
injury_claim: Claim amount for injuries,
property_claim: Claim amount for property damage,
vehicle_claim: Claim amount for vehicle damage,
auto_make: Make of the involved vehicle,
auto_model: Model of the involved vehicle,
auto_year: Year of the involved vehicle,
fraud_reported: Whether the claim is reported as fraudulent (1) or not (0),


Data Featuring
age_group: The age category of "Young adult" "Adult" and "Senior".
Years_as_customer: The number of years the customer has been with the insurance company.
Vehicle_age: Age of the insured vehicle.
adjusted_csl: Adjusted coverage limits.
adjusted_deductible: Adjusted deductible amount, which is the amount the insured has to pay out of pocket before the insurance company pays the rest
adjusted_annual_premiums: Adjusted annual premiums, which is the amount the customer pays annually for the insurance coverage
adjusted_additional_services: Additional services adjusted to the policy, which could include things like roadside assistance, rental car coverage, etc
loss_amount: The amount of loss or claim filed by the customer.
weekday: The day of the week when the policy event occurred.
Month: The month when the policy event occurred.
Policy_year_bind: The year when the policy was bound or initiated.


This project represents a strategic initiative to leverage the power of data analytics to drive innovation, optimize performance, and deliver exceptional value to our customers. Through collaboration, innovation, and a relentless focus on excellence, we are poised to navigate the evolving landscape of the insurance industry and emerge as a leader in delivering superior customer outcomes.
