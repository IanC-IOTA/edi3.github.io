---
layout: default
---
# Supply Chain Standards for Web Developers

## Purpose of this site

Standards organisations such as [UN/CEFACT](https://www.unece.org/cefact/) and others have provided global leadership in electronic data interchange (EDI) standards for many decades through high quality outputs such as [UN/EDIFACT](http://www.unece.org/cefact/edifact/welcome.html) and [XML Schema](http://www.unece.org/cefact/xml_schemas/index). The vast majority of electronic international trade transations today are implemented using these EDI standards.

The rise of web platforms that exchange data via RESTful JSON APIs presents a new paradigm for B2B data exchange. But developers of web platforms rarely look to EDI standards to guide the design of their APIs. The purpose of this site is make semantic standards that embed decades of business domain knowledge accessible to web developers. The site also support interoperable implementations through open tooling, implememntations, and test harnesses.

If you are a provider of platforms or services to the international supply chain and are implementing (or plan to implement) APIs then you will be interested in the specifications provided by this site. Check out the [business case](https://edi3.org/business-case/) page to understand the value of edi3 specifications.

## Scope of our work

We publish technical specifications in three categories:

* **[Semantic Specifications:](https://edi3.org/semantic-specs/)** The primary output of this site. A suite of  Open API 3.0 interface specifications and JSON-LD semantic definitions to support consistent and interoperable implementations of trade, transport, financial, and regulatory process APIs in the international supply chain. 
* **[Technical Specifications:](https://edi3.org/technical-specs/)** Cross-platform interoperability needs consistency at the technical layer too. This suite of specifications does not re-invent existing technical standards but rather provides rules and patterns for consistent use of them. For example standard OAuth2.0 claims & scopes and standard W3C WebSub event header metadata. We also provide a resource discovery mechanism based on DNS that allows a find the API URL given a business identifier like a business number or container number.
* **[Tools & Methods:](https://edi3.org/tools-and-methods/)** A rather more specialist suite of specifications that are really only of interest if you are a modelling tool vendor or a contributor to the semantic specifications on this site (i.e. you are a user of conformant tools). These specifications help to ensure quality and consistency in the work of transforming established UN/CEFACT semantic models into the Open API and JSON-LD specifications on this site.

## Governance and Compliance

Quality matters. If critical trade documents like invoices, manifests, bills of lading, and so on are to be successfully exchanged between independent platforms than we need;

* strong processes to ensure the quality of our specifications, and
* clear conformance criteria and test harnesses to ensure the quality of implementations.

Read more about edi3 quality controls on the [Governance](https://edi3.org/governance/) page.

## How to participate

There are several levels of participation that you can choose from.  Pick any or all of the following:

* **Keep Informed**.  [Subscribe](https://eepurl.com/dMLfdU) to the regular edi3 newsletter.  We'll update you about the latest developments and opportunities at most once per week and you can un-subscribe anytime.
* **Join the conversation**,  [Join](https://join.slack.com/t/edi3/shared_invite/enQtNTY5OTkzMjQ0NjcyLTAxZGVlMzJmNWQ5MDBjOTRmMWViNGU0MzdhY2VkOWIwZWY3ODMxOWE4YTJmZjdiNTBkYzczZDk5Y2ViOWJlNzQ){:target="_blank"}) the edi3 Slack team and subscribe to as many channels as you wish (there's one for each spec and a general channel).  You can join the conversation, make suggestions, or ask questions and get help.
* **Help with development**.  [Github](https://github.com/edi3) is our main tool for development of the edi3 specifications and reference implementations. It's all in the open and all open source.  Feel free to leave us comments or report a bug in the relevant GitHub issue list. Your contributions remain your IP but you should be prepared to release your IP if and when any edi3 specifications are offered as initial contributions to formal standards work at UN/CEFACT or other similar entities. 

