# 📚 ISC2 Certified in Cybersecurity (CC) Study Notes

## 🛡️ Domain 1: Security Principles

### 🔺 The CIA Triad
The core foundation of information security consists of three essential elements:
* **Confidentiality:** Preventing unauthorized access to information.
* **Integrity:** Ensuring information is accurate and not improperly altered.
* **Availability:** Ensuring information and systems are accessible when authorized users need them.

---

### 📊 Risk Management & Matrix Prioritization
Security controls are implemented during the risk management process to mitigate risks to a level deemed acceptable by the entity. The primary purpose of a **Risk Matrix** is to prioritize risks based on their **Likelihood (Probability)** and **Impact**.



[Image of a risk matrix]


| Probability (Likelihood) | Impact (Severity) | Priority Level / Description |
| :--- | :--- | :--- |
| **High** | **High** | **Critical (Most Important)** - Requires immediate mitigation. |
| **High** | **Low** | **Medium** - Operational nuisance; managed through procedures. |
| **Low** | **High** | **High** - Major disasters; managed via insurance/transfer or DRP. |
| **Low** | **Low** | **Low** - Acceptable risk; monitored over time. |

> 💡 **Real-World Application:** Calculating premium payments against potential financial payouts is exactly how companies offer identity theft insurance to manage their own financial risk.
> 
> 🏛️ **Governance:** Responsibility for setting risk management priorities ultimately belongs to **Executive Management** and the **Board of Directors**.

---

### 🔑 Authentication & Identity
* **Authentication:** The process of verifying or proving a user's identity. 
* **Multi-Factor Authentication (MFA):** Requiring **two or more different** authentication factors:
  * 🧠 *Something you know:* Passwords, passphrases, or PINs.
  * 💳 *Something you have:* Hard tokens, memory cards, or smart cards.
  * 🧬 *Something you are:* Biometrics (fingerprints, retina scans, measurable characteristics).
* **Personally Identifiable Information (PII):** Information that, when used alone or combined with other data, significantly narrows the association to a specific individual.

---

### ⚖️ Regulatory Compliance & Industry Standards
Organizations utilize external frameworks to build internal security structures.

#### International & National Standard Bodies:
* **ISO:** International Organization for Standardization
* **NIST:** National Institute of Standards and Technology
* **IETF:** Internet Engineering Task Force (focuses on Internet architecture)

#### Critical Regulations:
* **HIPAA:** Health Insurance Portability and Accountability Act (Privacy of medical info in the U.S.).
* **GDPR:** General Data Protection Regulation (Strict data protection law in the European Union).

#### The Compliance Hierarchy:
Governance teams use standards to create frameworks, which flow downward in strict order of authority:
$$\text{Regulations} \rightarrow \text{Standards} \rightarrow \text{Policies} \rightarrow \text{Procedures}$$

* **Regulations:** Laws issued by governments. Non-compliance typically carries heavy financial penalties.
* **Policies:** High-level guidance put in place by organizational governance (executive management).
* **Standards:** Mandatory rules or frameworks used to introduce policies and procedures.
* **Procedures:** Detailed, step-by-step instructions to complete specific tasks supporting policies.

---

### 🧠 Core Risk Terminology
* **Asset:** Something of value in need of protection.
* **Vulnerability:** A gap, flaw, or weakness in protection efforts.
* **Threat:** Something or someone aiming to exploit a vulnerability to cause harm.
* **Code of Ethics:** Information security professionals must act honorably, honestly, justly, responsibly, and legally.
* **Risk Identification Takeaways:** 1. Identify risk to communicate it clearly.
  2. Employees at **all levels** of an organization are responsible for identifying risk.
  3. Security professionals' primary role at the system level is **assisting** in risk assessments.

---

## 🚨 Domain 2: Incident Response, BC, & DR Concepts

### 📑 The Operational Defense Framework
When operating conditions shift unexpectedly, organizations rely on three distinct phases of safety and recovery planning:

```text
🚨 Unexpected Incident ──> 🛡️ Incident Response Plan (Keep business operating)
                                 │
                     If disruption continues...
                                 ▼
                           💼 Business Continuity Plan (Sustain baseline operations)
                                 │
                     If primary systems fail completely...
                                 ▼
                           💥 Disaster Recovery Plan (Rebuild and restore IT)
