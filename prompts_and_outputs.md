# Prompts and AI Outputs

## Prompt Library v1 — Customer Support Replies

**Author:** Laiba
**Internship:** Neurofive Solutions
**AI Tool:** ChatGPT
**Use Case:** Customer Support Replies
**Version:** 1.0
**Date:** August 2026

---

## 1. Purpose

This file contains the five customized prompts created from the same reusable customer-support prompt template, along with their corresponding AI-generated outputs.

The purpose is to demonstrate that one reusable prompt structure can be adapted to multiple customer-support situations by changing only the relevant variables.

---

# Prompt 1 — Damaged Order

## Variables Used

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

## Complete Prompt

```text
ROLE:

You are a professional customer support representative for TechStore.


CONTEXT:

A customer has contacted the company regarding a damaged product.

Customer message:

"My laptop arrived with a cracked screen. I was really excited
to receive it, but now I can't use it."

Relevant information:

The customer ordered the laptop three days ago. The package has
already been delivered.


TASK:

Write a helpful and professional response to the customer.
Acknowledge their concern, provide an appropriate solution,
and explain the next steps clearly.


FORMAT:

Write the response as a customer-support email containing:

- A professional greeting
- Acknowledgment of the customer's issue
- Appropriate solution or next steps
- Professional closing


CONSTRAINTS:

- Use a professional and empathetic tone.
- Keep the response between 80 and 120 words.
- Do not blame the customer.
- Do not invent information that has not been provided.
- Keep the language clear and easy to understand.
- Focus directly on the customer's issue.
```

## AI Output

**Subject: Assistance With Your Damaged Laptop**

Dear Customer,

We're sorry to hear that your laptop arrived with a cracked screen. We understand how disappointing it must be to receive your order in this condition, especially after looking forward to using it.

Please do not attempt to use the damaged device. We can help you with the next steps for resolving the issue. Please provide photographs of the damaged screen and packaging so our support team can review the condition of the delivery and assist you further.

We apologize for the inconvenience and appreciate your patience while we work to resolve this matter.

Best regards,
TechStore Customer Support

---

# Prompt 2 — Late Delivery

## Variables Used

```text
COMPANY_NAME = TechStore

CUSTOMER_ISSUE = Late delivery

CUSTOMER_MESSAGE =
"My package was supposed to arrive five days ago, but I still
haven't received it. Can you tell me where it is?"

ADDITIONAL_INFORMATION =
The tracking information indicates that the package has been delayed.

MIN_WORDS = 80

MAX_WORDS = 120
```

## Complete Prompt

```text
ROLE:

You are a professional customer support representative for TechStore.


CONTEXT:

A customer has contacted the company regarding a late delivery.

Customer message:

"My package was supposed to arrive five days ago, but I still
haven't received it. Can you tell me where it is?"

Relevant information:

The tracking information indicates that the package has been delayed.


TASK:

Write a helpful and professional response to the customer.
Acknowledge their concern, provide an appropriate solution,
and explain the next steps clearly.


FORMAT:

Write the response as a customer-support email containing:

- A professional greeting
- Acknowledgment of the customer's issue
- Appropriate solution or next steps
- Professional closing


CONSTRAINTS:

- Use a professional and empathetic tone.
- Keep the response between 80 and 120 words.
- Do not blame the customer.
- Do not invent information that has not been provided.
- Keep the language clear and easy to understand.
- Focus directly on the customer's issue.
```

## AI Output

**Subject: Update Regarding Your Delayed Package**

Dear Customer,

We apologize for the delay with your delivery and understand your concern about not receiving your package as expected.

According to the available tracking information, your package has unfortunately been delayed. We understand that this is frustrating, particularly since the expected delivery date has already passed.

Our support team can assist you in reviewing the latest tracking status and determining the appropriate next steps. We recommend keeping your tracking information available when contacting our team so we can assist you as efficiently as possible.

Thank you for your patience and understanding.

Best regards,
TechStore Customer Support

---

# Prompt 3 — Refund Request

## Variables Used

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

## Complete Prompt

```text
ROLE:

You are a professional customer support representative for TechStore.


CONTEXT:

A customer has contacted the company regarding a refund request.

Customer message:

"I would like to return this product and receive a refund."

Relevant information:

The customer purchased the product 10 days ago and wants to
return it.


TASK:

Write a helpful and professional response to the customer.
Acknowledge their concern, provide an appropriate solution,
and explain the next steps clearly.


FORMAT:

Write the response as a customer-support email containing:

- A professional greeting
- Acknowledgment of the customer's issue
- Appropriate solution or next steps
- Professional closing


CONSTRAINTS:

- Use a professional and empathetic tone.
- Keep the response between 80 and 120 words.
- Do not blame the customer.
- Do not invent information that has not been provided.
- Keep the language clear and easy to understand.
- Focus directly on the customer's issue.
```

## AI Output

**Subject: Assistance With Your Return and Refund Request**

Dear Customer,

Thank you for contacting TechStore. We understand that you would like to return your recent purchase and request a refund.

We can assist you with the return process. Since your purchase was made 10 days ago, our support team can review the order details and provide the appropriate next steps for returning the product.

Please have your order information available when contacting our support team so we can locate your purchase and guide you through the process.

We appreciate you reaching out to us and apologize for any inconvenience.

Best regards,
TechStore Customer Support

---

# Prompt 4 — Password Reset

## Variables Used

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

## Complete Prompt

```text
ROLE:

You are a professional customer support representative for TechStore.


CONTEXT:

A customer has contacted the company regarding a password reset.

Customer message:

"I forgot my password and can't access my account."

Relevant information:

The customer still has access to the email address registered
with their account.


TASK:

Write a helpful and professional response to the customer.
Acknowledge their concern, provide an appropriate solution,
and explain the next steps clearly.


FORMAT:

Write the response as a customer-support email containing:

- A professional greeting
- Acknowledgment of the customer's issue
- Appropriate solution or next steps
- Professional closing


CONSTRAINTS:

- Use a professional and empathetic tone.
- Keep the response between 60 and 100 words.
- Do not blame the customer.
- Do not invent information that has not been provided.
- Keep the language clear and easy to understand.
- Focus directly on the customer's issue.
```

## AI Output

**Subject: Help With Resetting Your Password**

Dear Customer,

We're happy to help you regain access to your TechStore account.

Since you still have access to the email address registered with your account, please use the password-reset option associated with your account to request a password reset. Follow the instructions sent to your registered email address to create a new password.

If you experience any difficulty during the process, please contact our support team for further assistance.

Best regards,
TechStore Customer Support

---

# Prompt 5 — Subscription Cancellation

## Variables Used

```text
COMPANY_NAME = TechStore

CUSTOMER_ISSUE = Subscription cancellation

CUSTOMER_MESSAGE =
"I want to cancel my monthly subscription."

ADDITIONAL_INFORMATION =
The customer wants the cancellation to become effective immediately.

MIN_WORDS = 60

MAX_WORDS = 100
```

## Complete Prompt

```text
ROLE:

You are a professional customer support representative for TechStore.


CONTEXT:

A customer has contacted the company regarding subscription cancellation.

Customer message:

"I want to cancel my monthly subscription."

Relevant information:

The customer wants the cancellation to become effective immediately.


TASK:

Write a helpful and professional response to the customer.
Acknowledge their concern, provide an appropriate solution,
and explain the next steps clearly.


FORMAT:

Write the response as a customer-support email containing:

- A professional greeting
- Acknowledgment of the customer's issue
- Appropriate solution or next steps
- Professional closing


CONSTRAINTS:

- Use a professional and empathetic tone.
- Keep the response between 60 and 100 words.
- Do not blame the customer.
- Do not invent information that has not been provided.
- Keep the language clear and easy to understand.
- Focus directly on the customer's issue.
```

## AI Output

**Subject: Subscription Cancellation Request**

Dear Customer,

Thank you for contacting TechStore. We understand that you would like to cancel your monthly subscription immediately.

Our support team can assist you with the cancellation process. Please provide or confirm your account information so the subscription can be located and the appropriate cancellation steps can be completed.

We appreciate your time with TechStore and are happy to assist you with your request.

Best regards,
TechStore Customer Support

---

# Testing Summary

| # | Scenario                  | Template Reused | Variables Changed          | Output Generated |
| - | ------------------------- | --------------- | -------------------------- | ---------------- |
| 1 | Damaged Order             | Yes             | Customer issue and context | Yes              |
| 2 | Late Delivery             | Yes             | Customer issue and context | Yes              |
| 3 | Refund Request            | Yes             | Customer issue and context | Yes              |
| 4 | Password Reset            | Yes             | Customer issue and context | Yes              |
| 5 | Subscription Cancellation | Yes             | Customer issue and context | Yes              |

---

# Overall Observation

The same Role + Context + Task + Format + Constraints framework was used for all five scenarios.

The main variables were changed according to the customer's situation, while the underlying instructions remained consistent.

The generated responses maintained a professional and empathetic customer-support style and followed the requested email format.

---

# Key Learning

This exercise demonstrated that reusable prompt templates can:

* Reduce repetitive prompt writing.
* Maintain consistency across different tasks.
* Make prompts easier to customize.
* Provide better control over AI-generated responses.
* Support multiple use cases using one core prompt structure.

---

# Conclusion

The five tests demonstrate the practical value of reusable prompt engineering. Instead of rewriting an entire prompt for every customer issue, the same structured template can be reused by changing only the relevant variables.

This approach makes prompt creation more efficient, consistent, scalable, and easier to maintain.

**Prompt Library v1 successfully demonstrates reusable prompt design for customer-support applications.**
