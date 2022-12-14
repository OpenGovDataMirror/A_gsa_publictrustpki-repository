---
title: Frequently Asked Questions
layout: docs
permalink: /faq/
---

# Frequently Asked Questions

- [What is the U.S. Federal Public Trust TLS PKI?](#what-is-the-us-federal-public-trust-tls-pki)
- [What kind of certificates will this service issue?](#what-kind-of-certificates-will-this-service-issue)
- [When will this service be available?](#when-will-this-service-be-available)
- [What are the requirements to use this service?](#what-are-the-requirements-to-use-this-service)
- [What is the relationship between the U.S. Federal Public Trust TLS PKI and the Federal PKI?](#what-is-the-relationship-between-the-us-federal-public-trust-tls-pki-and-the-federal-pki)
- [Who can I contact for support or to report an incident?](#who-can-i-contact-for-support-or-to-report-an-incident)


## What is the U.S. Federal Public Trust TLS PKI?
The U.S. Federal Public Trust Transport Layer Security (TLS) Public Key Infrastructure (PKI) is a collaborative service offering planned by the General Services Administration and the Defense Information Systems Agency. Since 2016, teams have  worked together to design and build a service that issues TLS certificates for federal DotGov and DotMil web services. 

**The U.S. Federal Public Trust TLS PKI will:**
- satisfy modern Web PKI requirements like Certificate Transparency and shorter certificate validity periods.
- be agile, purpose-driven, open, and transparent.
- promote automation to improve U.S. Federal Government efficiencies.
- be separate from the Federal Public Key Infrastructure.


## What kind of certificates will this service issue?
The service will issue Transport Layer Security (TLS) certificates for your web services, compliant with modern Web PKI standards and best practices.

## When will this service be available?

**Best-case scenario**, we could begin issuing publicly-trusted TLS certificates **Q1 FY 2021**.

Why so long from now? Well, there's a lot that goes into building a publicly-trusted Public Key Infrastructure. We must:
- write policies, practices, and procedures.
- build and audit Certification Authorities.
- submit applications to commercial trust store and Certificate Transparency Log operators to facilitate global trust.

We **cannot** guarantee commercial trust store operators like Microsoft, Apple, or Mozilla will approve our application for distribution. 


## What are the requirements to use this service?

Your web service must be: 
- a **federal** DotGov or DotMil web service.
- **internet-accessible**.
- able to support the **Automated Certificate Management Environment** protocol. 


## What is the relationship between the U.S. Federal Public Trust TLS PKI and the Federal PKI?
The Federal Public Key Infrastructure (FPKI) issues and manages person identity and **enterprise** device identity certificates for the Federal Government and mission partners. 

The Public Trust PKI will be a separate and distinct PKI with a single focus - the issuance of **publicly-trusted** TLS certificates to federal DotGov and DotMil web services.

## Who can I contact for support or to report an incident?
For general questions, email us at <a href="mailto:{{site.email}}">{{site.email}}</a>.

To report an incident, review our [incident reporting procedures]({{site.baseurl}}/docs/incident-reporting).
