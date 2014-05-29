
## The Specific Questions Asked In the RFI
*[copy and paste individual questions along with your responses into your email response]*

### Section A. Information Gaps and Needs in Accessing Current Data and Aid Programs

*Section A, Question 1*: How could data sets that are already publicly available be made more accessible using APIs? Are there specific data sets that are already available that would be most likely to inform consumer choice about college affordability and performance? 

Data sets that are updated on an annual basis could better be used in an-up-to-date fashion if accessed through an API, freeing the consumer of the data set of the burden of annual refreshing the data.  I am unfamiliar with what datasets are currently available.  However, I believe if APIs were made available that included costs for specific institutions, a programmer could and would combine this with non-education data, such as the cost of living within a city, to produce an application that accurately computed overall costs of attending an institution.  It would not be the Department of Education's responsibility to tie these together, but rather to offer just the educational-institution specific API and an API for student aid.  I personally believe this would really come alive only when tied in (by a third party) with geographic data that would allow the cost of visits home to be computed, for example.
 
*Section A, Question 2*: How could APIs help people with successfully and accurately completing forms associated with any of the following processes: FAFSA; Master Promissory Note; Loan Consolidation; entrance and exit counseling; Income-Driven Repayment (IDR) programs, such as Pay As You Earn; and the Public Student Loan Forgiveness program?

I believe the overriding need is so reduce the need to enter duplicate data and to inform people of various programs.  If possible, the DoEd should produce a "data locker", or use a different one, to reduce the need to redundantly enter data, and to keep this data more secure.  A third-party could potentially perform this function, utilizing multiple APIs to assist in the completion of these forms.
  
*Section A, Question 3*: What gaps are there with loan counseling and financial literacy and awareness that could be addressed through the use of APIs to provide access to government resources and content?  

I believe an API which tied a particular Educational status to income level, job security, and job satisfaction could be helpful.  This could be presented either by DoEd or a 3rd party as theme-specific portals, such as the STEM portal or the humanities portal.

*Section A, Question 4*: What services that are currently provided by title IV student loan servicers could be enhanced through APIs (e.g., deferment, forbearance, forgiveness, cancellation, discharge, payments)?  
*Section A, Question 5*: What current forms or programs that already reach prospective students or borrowers in distress could be expanded to include broader affordability or financial literacy information?  

### Section B. Potential Needs To Be Filled by APIs

*Section B, Question 1*: If APIs were available, what types of individuals, organizations, and companies would build tools to help increase access to programs to make college more affordable?  

I believe both for-profit and non-profit organization would build tools that helped prospective students make decisions about attending higher-education.  Financial aid would also be addressed.  Companies that offer financing would attempt to take advantage of this.  Some very large companies might also use this is a skilled-worker recruiting aid.

For example, the existing FAFSA application process is too linear in nature.  It gives me no feedback about the possibility of financial aid until completing the entire process.  It forces a large number of decisions, including the schools to attend, to be made up front, rather than recognizing that school selection is actually a complex feedback process.  An API that could submit a FAFSA application could allow third-party software to address this.  It is even possible that it would make it easier for teams within the DoEd to do a better job with this interface, while mitigating the risk of making back-end changes.

*Section B, Question 2*: What applications and features might developers, schools, organizations, and companies take interest in building using APIs in higher education data and services?  

* A "Total College Cost Computation" application that included geographic information, likely financial aid, and filtering of applicable universities.
* Regional College Information portals.  For example, the State of Texas might subsidize the "Texas College Resource Portal."
* Universities should be able to using an writable API to publish:
** Acceptance/application statistics
** Graduation rates
** Graduation employment rates
** Internship rates
* Special needs portals might be created by developers for applicants with special needs, such as veterans.

*Section B, Question 3*: What specific ways could APIs be used in financial aid processes (e.g., translation of financial aid forms into other languages, integration of data collection into school or State forms)?  

As mentioned above, APIs could allow software to be constructed that makes the application process more interactive and informative, by separating data collection somewhat from the formal act of sending in the application.  For example, someone could enter a partially completed FAFSA, receive and estimate of financial aid, become aware or expected costs, and then make changes to their selected school, all while technically working within the current FAFSA submission process, although this is not currently supported by the FAFSA website.

*Section B, Question 4*: How can third-party organizations use APIs to better target services and information to low-income students, first-generation students, non-English speakers, and students with disabilities? 

I view this question as closely related to "How could the Society of Lilliputian Sofware Engineers use APIs to provide better services to Lilliputians?"  In the end, target marketing, or simply tailoring, to a given market allows a better experience.

For example, an organization for Disabled Veterans could integrate the existing FAFSA website with a map of VA hospitals and could present institution-provided maps of handicapped accessible facilities.

I suppose a faith-based organization could also wish to relate school choices to school demographics and the physical location of churches, for example.

A writeable-API could be created to allow students to publish their needs for financial aid or other needs, which could then be utilized by companies to market services to those students.
 
*Section B, Question 5*: Would APIs for higher education data, processes, programs or services be useful in enhancing wraparound support service models? What other types of services could be integrated with higher education APIs?  

Housing location services, summer employment location services, community service opportunities, tax form completion services, could all be integrated with higher education APIs.  For example, some people might be willing to move to a city to obtain a degree, but only if they believe there are summer employment opportunities present in that city.  Many students will be working and earning a modest income, and some of them will be paying taxes for the very first time, so may want information about that.  Some students, such as those that are married or have children, may not have their housing needs well addressed by traditional College housing.  This is a fine opportunity for 3rd-party companies to provide a service at a profit.

### Section C. Existing Federal and Non-Federal Tools Utilizing APIs

*Section C, Question 1*: What private-sector or non-Federal entities currently offer assistance with higher education data and student aid programs and processes by using APIs? How could these be enhanced by the Department's enabling of additional APIs?  
*Section C, Question 2*: What private-sector or non-Federal entities currently work with government programs and services to help people fill out government forms? Has that outreach served the public and advanced public interests?  
*Section C, Question 3*: What instances or examples are there of companies charging fees to assist consumers in completing otherwise freely available government forms from other agencies? What are the advantages and risks to consider when deciding to allow third parties to charge fees to provide assistance with otherwise freely available forms and processes? How can any risks be mitigated?  

I personally recommend a policy "Before you charge a fee, the user must be made aware of the free services offered by DofEd."  I do believe this would require attention to enforce, but you need not worry about that until it starts happening.  Remember, you can retain control of the API.  If you decide it providing more detriment than benefit, you can shut the whole thing off.

*Section C, Question 4*: Beyond the IRS e-filing example, what other similar examples exist where Federal, State, or local government entities have used APIs to share government data or facilitate participation in government services or processes—particularly at a scale as large as that of the Federal Student Aid programs?  

### Section D. Technical Specifications

*Section D, Question 1*: What elements would a read-write API need to include for successful use at the Department?  

APIs should be RESTful and produce JSON.

*Section D, Question 2*: What data, methods, and other features must an API contain in order to develop apps accessing Department data or enhancing Department processes, programs, or services?  

This is highly dependent on the sort of functionality being offered.

*Section D, Question 3*: How would read-only and/or read-write APIs interact with or modify the performance of the Department's existing systems (e.g., FAFSA on the Web)? Could these APIs negatively or positively affect the current operating capability of such systems? Would these APIs allow for the flexibility to evolve seamlessly with the Department's technological developments?  

With suitable precautions, you should allow a FAFSA application to be submitted through a writable API.  This does bring with it certain risks:

* Increased applications (this is also a *benefit*)
* Increased applications which are not high-quality applications
* Denial-of-service attacks
* Lending legitimacy to bad-actors who would collect or negligently safegard PII (I notice that the FASFA askes for Social Security Number now.)


However, all of these risks can be dealt with proper design of the throttling and othe controls on the API.

In all probability, these APIs will increase the ease of making technical process within DoEd by allowing your own teams to consume the APIs effectively.

*Section D, Question 4*: What vulnerabilities might read-write APIs introduce for the security of the underlying databases the Department currently uses?  

As a rule of thumb, whenever anyone writes something to you it is a "publication" to you.  A University may "publicize" there average SAT score.  There should be no sense in which outsiders write to official DofEd database accept to "apply" or to publicize something.

For example, I could use FASFA today to submit an false financial aid application.  With an API I can do this as well, only faster.  Both of these actions should be treated the same by the DofEd.  I don't know how you prevent fraudulent applicatins today, but the same process would apply.

I do think you should think "Read APIs first, Write APIs second."


*Section D, Question 5*: What are the potential adverse effects on successful operation of the Department's underlying databases that read-write APIs might cause? How could APIs be developed to avoid these adverse effects?  
*Section D, Question 6*: How should APIs address application-to-API security?  
*Section D, Question 7*: How should the APIs address API-to-backend security issues? Examples include but are not limited to authentication, authorization, policy enforcement, traffic management, logging and auditing, TLS (Transport Layer Security), DDoS (distributed denial-of-service) prevention, rate limiting, quotas, payload protection, Virtual Private Networks, firewalls, and analytics.  
*Section D, Question 8*: How do private or non-governmental organizations optimize the presentation layer for completion and accuracy of forms?  
*Section D, Question 9*: What security parameters are essential in ensuring there is no misuse, data mining, fraud, or misrepresentation propagated through use of read-only or read-write APIs?  
*Section D, Question 10*: With advantages already built into the Department's own products and services (e.g., IRS data retrieval using FAFSA on the Web), how would new, third-party API-driven products present advantages over existing Department resources?  
*Section D, Question 11*: What would an app, service or tool built with read-write API access to student aid forms look like?  

### Section E. Privacy Issues

*Section E, Question 1*: How could the Department use APIs that involve the use of studentrecords while ensuring compliance with potentially applicable statutory and regulatory requirements, such as the Family Educational Rights and Privacy Act (2\*: U.S.C. 1232g; 3\*: CFR Part 99\*: and the Privacy Act (5 U.S.C. 552\*: and 3\*: CFR Part 5b)?  
*Section E, Question 2*: How could APIs ensure that the appropriate individual has provided proper consent to permit the release of privacy-protected data to a third party? How can student data be properly safeguarded to prevent its release and use by third parties without the written consent often required?  
*Section E, Question 3*: How might read-only or read-write APIs collect, document, and track individuals' consent to have their information shared with specific third parties?  
*Section E, Question 4*: How can personally identifiable information (PII) and other financial information (of students and parents) be safeguarded through the use of APIs?  
*Section E, Question 5*: What specific terms of service should be enabled using API keys, which would limit use of APIs to approved users, to ensure that information is not transmitted to or accessed by unauthorized parties?  
*Section E, Question 6*: What are the relative privacy-related advantages and disadvantages of using read-only versus read-write APIs for student aid data?  

### Section F. Compliance Issues

*Section F, Question 1*: What are the relative compliance-related advantages and disadvantages of using read-only versus read-write APIs for student aid data?  
*Section F, Question 2*: How can the Department prevent unauthorized use and the development of unauthorized products from occurring through the potential development of APIs? How might the Department enforce terms of service for API key holders, and prevent abuse and fraud by non-API key holders, if APIs were to be developed and made available?  
*Section F, Question 3*: What kind of burden on the Department is associated with enforcing terms and conditions related to APIs? 

This is so dependent on the policies in question that it is very difficult to answer.

*Section F, Question 4*: How can the Department best ensure that API key holders follow all statutory and regulatory provisions of accessing federal student aid funds and data through use of third-party products?  
*Section F, Question 5*: How could prior consent from the student whom the data is about be provided for release of privacy-protected data to third party entities? 

I believe this can be handled by OAuth-like methods.  I am not an expert in this, but I believe it can be solved.  An example is the way Google can be used to log into third-party applications.
 
*Section F, Question 6*: How should a legal relationship between the Department and an API developer or any other interested party be structured? 

It is important to note that in some cases, for read-only APIs, there might need to be no legal relationship at all.  This depeneds greatly on what is being offered.  I suggest you gradually and iteratively release more and more power in your APIs over a long period of time and only deal with the legal ramifcations of each step as it arises.
 
*Section F, Question 7*: How would a legal relationship between the Department and an API developer or any other interested party affect the Department's current agreements with third-party vendors that operate and maintain the Department's existing systems?  
*Section F, Question 8*: What disclosures should be made available to students about what services are freely available in government domains versus those that could be offered at a cost by a third party?  

I think you should force a complete disclosure of all free services by the DofEd.

*Section F, Question 9*: If the Department were to use a third-party application to engage with the public on its behalf, how could the Department ensure that the Department follows the protocols of OMB Memorandum 10-23?  

### Section G. Policy Issues

*Section G, Question 1*: What benefits to consumers or the Department would be realized by opening what is currently a free and single-point service (e.g., the FAFSA) to other entities, including those who may charge fees for freely-available services and processes? What are the potential unintended consequences?  

Benefits to consumers would, I hope, if implemented, include:
* A better FASFA application process,
* A better ability to make a decision about attending college through a more comprehensive information applcation,
* A better ability to select an institution by combinging financial aid data with other data *not* provided by the DofEd,
* The construction of regional and special-interest portals that cater to socio-economic classes or regions or interests (such as STEM.)


*Section G, Question 2*: How could the Department ensure that access to title IV, HEA student aid programs truly remains free, even amidst the potential development of third-party apps that may charge a fee for assistance in participating in free government programs, products, and services with or without providing legitimate value-added services?  

Not every API requires this sort of protection.  For example, simple read-only APIs that access a dataset probably do not rais much concern.  For other APIs, such as a FAFSA-write/submission API, I would recommend that you right legal terms of service that force clients of the API to inform users of the existing DofEd alternatives (presumably free.)  I would also recommend allocation at least one person to enforcement of this---although probably only person would be needed, if they were backed by the power to write cease-and-desist letters and revoke API keys.


*Section G, Question 3*: What other policy concerns should the Department consider with regard to the potential development of APIs for higher education data and student aid processes at the Department? 

The number one policy should be informing the users of re-provided services of existing DoEd resources. 
 
*Section G, Question 4*: How would APIs best interact with other systems already in use in student aid processes (e.g., within States)?  
*Section G, Question 5*: How would Department APIs benefit or burden institutions participating in title IV, HEA programs?  

The APIs provide two risks/burdens as I see it.
* There is a minor risk of performance degradation associated with Read-Only APIs. This can be addressed effectively by throttling, I believe.
* A large risk is associated with write-APIs, in terms of spam, denial-of-service, or even simply increasing the number of applications in a way that DofEd is not prepared to support. This would have to be addressed by an engineering staff on a case-by-case basis.

*Section G, Question 6*: While the Department continues to enhance and refine its own processes and products (e.g., through improvements to FAFSA or the IDR application process), how would third-party efforts using APIs complement or present challenges to these processes?

The biggest challenge would be over-use of write-APIs.  I doubt read-apis would actually be a problem.  A phased approach, of offering readable APIs before writable APIs, is usually a good idea.

However, it an important advantage of offering APIs as quickly as possible is that you immediately turn this question into a "yes, and..." debate rather than an "either/or" debate.  In general, you won't be able to accurately predict the creative ways in which an API may be used.  Remember, you never have to make a legal promise to leave the API open.  If YOU decide that it is not in the interest of the American people for whatever reason, just turn it off.  Opening a API is a decision set in wax, not concrete.  


