# Generating_keywords_for_SearchCampaigns

![Work Laptop](https://github.com/rd9437/Generating_keywords_for_SearchCampaigns/raw/main/work_laptop.png)


Imagine working for a digital marketing agency, and the agency is approached by a massive online furniture retailer. They want to test your skills at creating large campaigns for all of their website. You are tasked with creating a prototype set of keywords for search campaigns for their sofas section. The client says that they want you to generate keywords for the following products:

- sofas
- convertible sofas
- love seats
- recliners
- sofa beds

The client is a low-cost retailer, offering many promotions and discounts. You will need to focus on such keywords. You will also need to move away from luxury keywords and topics, as you are targeting price-sensitive customers. Because they are going to be tight on budget, it would be good to focus on a tightly targeted set of keywords and make sure they are all set to exact and phrase match.

Based on the brief above you will first need to generate a list of words, that together with the products given above would make for good keywords. Here are some examples:

- Products: sofas, recliners
- Words: buy, prices

The resulting keywords: 'buy sofas', 'sofas buy', 'buy recliners', 'recliners buy', 'prices sofas', 'sofas prices', 'prices recliners', 'recliners prices'.

As a final result, you want to have a DataFrame that looks like this:-

<table>
<thead>
<tr>
<th>Campaign</th>
<th>Ad Group</th>
<th>Keyword</th>
<th>Criterion Type</th>
</tr>
</thead>
<tbody>
<tr>
<td>Campaign1</td>
<td>AdGroup_1</td>
<td>keyword 1a</td>
<td>Exact</td>
</tr>
<tr>
<td>Campaign1</td>
<td>AdGroup_1</td>
<td>keyword 1b</td>
<td>Exact</td>
</tr>
<tr>
<td>Campaign1</td>
<td>AdGroup_2</td>
<td>keyword 2a</td>
<td>Exact</td>
</tr>
</tbody>
</table>
