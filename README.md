<p align="center">
  <h3 align="center">Customer-Flagging-Pipeline</h3>
</p>

<p align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&center=true&vCenter=true&width=435&lines=End-to-end+news+scraping" alt="Typing SVG" /></a>
</p>

<p align="center">
  Bank sector need to trace transactional data for their customer. the goals is to identify which credit in/out transaction. Credit in indicate the customer name is listed on data warehouse. So, they need data processing pipeline for identifying exact customer name based on data warehouse from a thousand hundred unstructured text. *Source code is confidential data*
</p>

---

### Program Tasks
1. **Load unstructured text & exact customer name data** -- Load data using pandas. The exact customer name data act like knowledge base and it gonna be match with unstructured text to ignore non-customer.
2. **Data Case Folding & Cleaning** -- Both data will be lowercased. Then, data will be cleaned from multiple whitespace and punctuation.
3. **Data Augmentation** -- Augment exact customer data to scale up data variety before the data is match with unstructured text. This approach will help to get more pattern of customer name. Augmented data will be store to Named Entity Recognition model with label "Customer"
4. 
5. **Data Matching** -- Match unstructured text with augmented data with fuzzy matching & Named Entity Recognition model. Fuzzy matching used for handle minor typo in unstructured text. Ex, the unstructured text is reference to `nvidia`, but the data is `nviidia`. Named Entity Recognition model used for exact matching. Ex, unstructured text contain `nvidia` only will be match with `nvidia`.
6. **Get Customer Id** -- Map matched customer with customer id, to get customer id.

---

### The Authors
<img alt="Salomo Hendrian Sudjono" title="Salomo Hendrian Sudjono" src="https://custom-icon-badges.demolab.com/badge/-Salomo%20Hendrian%20Sudjono-blue?style=for-the-badge&logo=person-fill&logoColor=white"/>
