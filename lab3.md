**Lab: Clickjacking with a frame buster script**
*- Goals: Perform Clickjacking that frames the account page and let user change their email accidentally.*
*- Analysis:*
1. These steps are similar to the others.
2. But, in this lab, `frame` tag is blocked by a script called `frame buster` that make us cannot use `<iframe src=...>`
3. Here, we can use overhead this by use an attribute is `sandbox="allow-forms allow-scripts"`
4. So we done with this.
*`SOLVED`*