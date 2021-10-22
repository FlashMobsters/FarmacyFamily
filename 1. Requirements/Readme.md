# Overview

Farmacy Family is an enhancement of the existing Farmacy Foods system (designed by Arch Colider from the first Kata exercise) that adds tighter engagement with
their customers.

When a transactional customer purchases a meal, Farmacy Family will generate an email elucidating additional benefits available for becoming an engaged customer.

# Primary Goals (Vision?)
- Develop relationships between engaged customers and nurture those relationships.
- Convert transactional customers to engaged customers.
- Generate analytical data from medical information to demonstrate the benefits of Farmacy Foods.

Thus, the overall goal of Farmacy Family is to connect, gather, analyze, and communicate.

# Users 
Hundreds, separated by distinct geographic zones. Additionally, different clusters of customers frequently consolidate around similar dietary requirements. Mostly targeting low income, elderly, and first responders

## Clients
- Building a community, education, increased awareness (learning/social platform)

## Clinics - Work with clinics to establish baseline tests for clients
- Gather results (from clinics or farmacy foods?)
- Test every 3 months (reminders/scheduling/follow ups? out of scope for platform?)
- Analyze results (in scope for platform? reporting/data mining required?)
- Demonstrate any change in their overall health (part of reporting?)
- Use this info to gain investors and additional support and help Dieticians (additional requirements or part of reports?)
- Farmacy Foods supported generic advice from dieticians. Farmacy Family will support one-on-one advice for engaged customers (in platform messaging vs conferencing vs in person?)
- Regular contact via messages (in platform?)
- Selective access to medical information about the customer from a partner clinic (consent from clients, API into partner clinics, data processing/analytics)

## Farmacy Foods
- Farmacy Family needs to know which Transactional Customers (and their information) are not part of Farmacy Family (Engaged Customer) to start the onboarding process for those customers 
- Farmacy Foods needs to know which transactional customers are Engaged Customers

# Requirements
- Add a new system to manage customer profiles, allowing community engagement, personalization around preferences and dietary needs
- Support geographical trend analysis to hone Farmacy Family’s ability to optimize the foods delivered to fridges (an additional integration point TO Farmacy Foods)
- Support both push and pull models for community engagement. In other words, Farmacy Family will manage forums,emails, and create connections between similar demographics. Farmacy Family needs transactional member information for outreach purposes. The engagement model includes subscriptions, forums, reference material, class information, and other media that supports Food-as-medicine
- eDietian has access customer profile to improve advice and monitoring of customers. (consent management)
- Additionally, the customer and dietitian can interact via messages. (in platform messaging vs external?)
- Farmacy Family wants to improve the distribution and potential food waste from having the wrong mix of foods in a particular fridge. (integration into Supply Chain)
- Farmacy Family will include medical profile information and the ability to share information with medical service providers. (consent management, integration with Medical Service Providers API / batch)
- Farmacy Family customers can customize how much profile information they want to allow the community to see, at a finegrained level. (consent management)
- Farmacy Family has relationships with third party providers (clinics, doctors, etc) that have access to more analytical data to improve engagement (for example, regional dietary observations). (data import/processing?)
- Add Farmacy Family user interface to existing Foods interface, which is currently a Reactive monolith. Create a holistic UX for both food and Farmacy Family to support engagement model. 

# Domain areas
## Onboarding
- profile for customer (CRM)
- analytics (data processing, warehousing, data lake, recommendations, machine learning, reporting, BI)

## Community
- forum (localized, temporal) (learning platform)
- in person / virtual events (localized, temporal) (calendar, scheduling, conferencing)
- classes (localized, temporal) (calendar, scheduling, conferencing)
- interactive media library (global, reference) (learning platform)
- general wellness education (global, reference) (learning platform)

## Integration (extranet)
- dietician (person vs external systems?)
- clinics (external systems?)
- Farmacy Foods (supply chain, reporting, UI)



