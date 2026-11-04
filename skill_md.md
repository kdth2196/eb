# Skill: AliExpress to eBay Dropshipping Automation

## Overview
This skill instructs Manus bot to research, source, filter, optimize, and list high-demand unbranded products from AliExpress onto an eBay seller account while ensuring full compliance with eBay policies.

---

## Core Guidelines & Rules

### 1. Product Sourcing Criteria
- **Source Platform:** AliExpress
- **Maximum Cost Price:** $\le \$10.00$ USD (including standard shipping where applicable).
- **Sales Criteria:** High rating ($\ge 4.5$ stars), high order volume, positive supplier feedback ($>95\%$).
- **Item Condition:** Brand new, unbranded / generic products ONLY.

### 2. Strict Compliance & Safety Rules
- **No Branded Products:** Strictly avoid trademarked names, logos, designer items, or branded replicas.
- **No Counterfeit Items:** Verify that products are 100% generic.
- **Policy Adherence:** Comply with all eBay listing policies, VERO (Verified Rights Owner Program) guidelines, and dropshipping regulations.
- **Restricted Categories:** Do not list weapons, hazardous materials, adult items, food/perishables, supplements, or medical devices.

---

## Workflow Steps

### Step 1: Product Research & Selection
1. Scan AliExpress for trending, best-selling products priced under **$10**.
2. Filter for items with reliable ePacket/standard tracking methods.
3. Verify that the product is completely unbranded and non-infringing.

### Step 2: Listing Optimization (SEO)
- **Title Optimization:**
  - Create a keyword-dense, high-converting title (up to 80 characters).
  - Use primary search terms (e.g., product type, key features, color/size, use case).
  - Avoid filler words like "L@@K", "WOW", or excessive punctuation.
- **Description Creation:**
  - Write a clear, professional, and persuasive HTML or plain-text product description.
  - Include key features, specifications, package contents, and usage instructions.
  - Emphasize benefits and fast shipping/customer service assurance.

### Step 3: Pricing & Listing Configuration
- **Profit Margin:** Apply standard profit margins and fee calculations previously configured in your default listing settings.
- **Item Specifics:** Fill in all relevant eBay item specifics (Brand: Unbranded, Type, Material, Color, MPN: Does Not Apply).
- **Shipping & Return Policies:** Use standard default shipping profiles, handling times, and return policies previously defined on the account.

---

## Command Syntax

```text
/dropship-list {input}
```
*Description:* Find best-selling AliExpress items matching `{input}` (or general top sellers if empty) under $10, filter for policy compliance, generate SEO title/description, and list on eBay using default account settings.