# Prompt Library v1

## Reusable Customer Support Reply Generator

**Author:** Laiba
**Internship:** Neurofive Solutions
**Use Case:** Customer Support Replies
**Version:** 1.0
**AI Tool:** ChatGPT
**Date:** August 2026

---

## 1. Introduction

This Prompt Library demonstrates the design and application of a reusable prompt template for generating professional customer-support replies.

Instead of creating a completely new prompt for every customer issue, one structured template is used with replaceable variables.

The template follows five consistent components:

1. Role
2. Context
3. Task
4. Format
5. Constraints

The template was adapted to five different customer-support scenarios to demonstrate its reusability.

---

## 2. Objective

The objective of this project is to create a reusable prompt template that can generate professional, clear, and empathetic customer-support responses for different situations.

The template should:

* Be reusable across different customer issues.
* Produce consistent response structures.
* Allow customer-specific information to be changed easily.
* Control the tone and length of generated responses.
* Reduce the need to rewrite prompts from scratch.

---

## 3. Master Prompt Template

### Role

You are a professional customer support representative for `{COMPANY_NAME}`.

### Context

A customer has contacted the company regarding `{CUSTOMER_ISSUE}`.

**Customer message:**

> "{CUSTOMER_MESSAGE}"

**Relevant information:**

`{ADDITIONAL_INFORMATION}`

### Task

Write a helpful and professional response to the customer. Acknowledge their concern, provide an appropriate solution, and explain the next steps clearly.

### Format

Write the response as a customer-support email containing:

* A professional greeting
* Acknowledgment of the customer's issue
* Appropriate solution or next steps
* Professional closing

### Constraints

* Use a professional and empathetic tone.
* Keep the response between `{MIN_WORDS}` and `{MAX_WORDS}` words.
* Do not blame the customer.
* Do not invent information that has not been provided.
* Keep the language clear and easy to understand.
* Focus directly on the customer's issue.

---

## 4. Prompt Variables

| Variable                   | Description                     |
| -------------------------- | ------------------------------- |
| `{COMPANY_NAME}`           | Name of the company             |
| `{CUSTOMER_ISSUE}`         | Customer's main issue           |
| `{CUSTOMER_MESSAGE}`       | Customer's original message     |
| `{ADDITIONAL_INFORMATION}` | Additional relevant context     |
| `{MIN_WORDS}`              | Minimum desired response length |
| `{MAX_WORDS}`              | Maximum desired response length |

These variables allow the same prompt structure to be reused for different customer-support scenarios.

---

## 5. Test Scenarios

The reusable template was tested on the following five scenarios:

1. Damaged Order
2. Late Delivery
3. Refund Request
4. Password Reset
5. Subscription Cancellation

The underlying prompt structure remained the same for all five tests.

---

## 6. Test 1 — Damaged Order

### Variables

```text
COMPANY_NAME = TechStore

CUSTOMER_ISSUE = Damaged product

CUSTOMER_MESSAGE =
"My laptop arrived with a cracked screen. I was really excited
to receive it, but now I can't use it."

ADDITIONAL_INFORMATION =
The customer ordered the laptop three days ago. The package
has already been delivered.

MIN_WORDS = 80

MAX_WORDS = 120
```

### Purpose

Test whether the template can generate an empathetic response for a damaged-product complaint.

---

## 7. Test 2 — Late Delivery

### Variables

```text
COMPANY_NAME = TechStore

CUSTOMER_ISSUE = Late delivery

CUSTOMER_MESSAGE =
"My package was supposed to arrive five days ago, but I still
haven't received it. Can you tell me where it is?"

ADDITIONAL_INFORMATION =
The tracking information indicates that the package has been
delayed.

MIN_WORDS = 80

MAX_WORDS = 120
```

### Purpose

Test whether the same template can handle a delivery-related issue.

---

## 8. Test 3 — Refund Request

### Variables

```text
COMPANY_NAME = TechStore

CUSTOMER_ISSUE = Refund request

CUSTOMER_MESSAGE =
"I would like to return this product and receive a refund."

ADDITIONAL_INFORMATION =
The customer purchased the product 10 days ago and wants to
return it.

MIN_WORDS = 80

MAX_WORDS = 120
```

### Purpose

Test whether the template can generate an appropriate response to a refund request without inventing a specific refund policy.

---

## 9. Test 4 — Password Reset

### Variables

```text
COMPANY_NAME = TechStore

CUSTOMER_ISSUE = Password reset

CUSTOMER_MESSAGE =
"I forgot my password and can't access my account."

ADDITIONAL_INFORMATION =
The customer still has access to the email address registered
with their account.

MIN_WORDS = 60

MAX_WORDS = 100
```

### Purpose

Test whether the template can be reused for an account-support issue.

---

## 10. Test 5 — Subscription Cancellation

### Variables

```text
COMPANY_NAME = TechStore

CUSTOMER_ISSUE = Subscription cancellation

CUSTOMER_MESSAGE =
"I want to cancel my monthly subscription."

ADDITIONAL_INFORMATION =
The customer wants the cancellation to become effective
immediately.

MIN_WORDS = 60

MAX_WORDS = 100
```

### Purpose

Test whether the same prompt structure can generate a response for a subscription-related request.

---

## 11. Prompt Reusability

The five prompts demonstrate that the majority of the prompt remains unchanged.

The reusable structure is:

```text
Role
+
Context
+
Task
+
Format
+
Constraints
```

Only the variables change:

```text
Company Name
Customer Issue
Customer Message
Additional Information
Word Limit
```

This makes the template similar to a reusable function in programming: the structure stays fixed while different inputs are provided.

---

## 12. Key Observations

The testing demonstrated the following:

* The same prompt structure can be applied to different customer-support situations.
* Changing the customer-specific variables changes the generated response.
* The Role section establishes the AI's responsibility.
* The Context section provides the information needed to understand the situation.
* The Task section defines the expected action.
* The Format section creates consistency in the output.
* The Constraints section helps control tone, length, and content.
* The template reduces the need to repeatedly write prompts from scratch.

---

## 13. Benefits of the Template

### Consistency

Responses follow a similar professional structure.

### Reusability

The template can be applied to many customer-support scenarios.

### Efficiency

Only the relevant variables need to be changed.

### Control

The prompt provides clear instructions about tone, format, and length.

### Scalability

Additional scenarios can easily be added without redesigning the entire prompt.

---

## 14. Possible Extensions

Future versions could include:

* Technical-support prompts
* Complaint-handling prompts
* Product-information prompts
* Multilingual customer support
* Different levels of response urgency
* Chatbot-specific versions
* Different brand tones
* Automated prompt generation using structured variables

---

## 15. Conclusion

Prompt Library v1 demonstrates how a reusable prompt template can be designed using Role, Context, Task, Format, and Constraints.

The same template was adapted to five customer-support scenarios by changing only the relevant variables.

This approach provides a systematic way to design prompts, improves consistency, reduces repetitive prompt writing, and makes the prompt easier to adapt to new situations.

The project demonstrates the practical application of reusable prompt engineering in a customer-support context.

---

## 16. Demo

A 2–3 minute demonstration video shows:

1. The reusable master prompt.
2. The prompt variables.
3. Live testing of two customer-support scenarios.
4. The resulting AI-generated responses.

**LinkedIn Demo:**
[Add LinkedIn Post URL Here]

---

## 17. Project Information

**Project:** Prompt Library v1
**Use Case:** Customer Support Replies
**AI Tool:** ChatGPT
**Author:** Laiba
**Internship:** Neurofive Solutions
**Version:** 1.0
