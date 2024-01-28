# MSES602
MSES 602 Course
## First Time using Github Markdown so I want to do some testing

<!--How to hide a comment-->
Some of the markdown is similar to HTML scripting. I like HTML better.  With Mark down you have to have the words right after and before the symbols, or they will not work, but you do get to see what it will look like before you preview.
<br>
**Testing Bold 1**
<br>
__Testing Bold 2__
<br>
<b>Here I use HTML to bold </b>
<br>
*Testing Italic 1*
<br>
*Testing Italic 2*
<br>
_Test Italic 3_
<br>
<i> Here I use HTML for italic</i>
~Strike Through~
<br>
***Bold and Italic***
<br>
Here we have example of <sub>Subscript</sub>
<br>
Here we have example of <sup>Superscript</sup>
<br>
>Markdown quote block
<blockquote>HTML block quote</blockquote>
<br>
To do an order list use one of the symbols below and a space between the item. It seem like you need to leave a line space to get it to work.
<br>

- order 1
  - order 2
* order 3
* order 4
+ order 5
+ order 6
1. order 7
1. order 8
<br>
Below I used HTML for order list.
<ul>
  <li>list 1</li>
  <li>list 2</li>
</ul>
<br>
Table test 1
<br>
<table>
  <caption>Table Test 1</caption>
  <tr>
    <th>header 1</th>
    <th>header 2</th>
  </tr>
  <tr>
    <td>detail 1</td>
    <td>detail 2</td>
  </tr>
</table>
<br>

Table Test 2
<br>
<table>
  <caption style="text-align:right">Table Test 2</caption>
  <tr>
    <th></th>  
    <th>header 1</th>
    <th>header 2</th>
  </tr>
  <tr>
    <th>Row 1</th>
    <td>detail 1</td>
    <td>detail 2</td>
  </tr>
</table>

<br>
How to make table with markdown.
<br>

| Rank | THING-TO-RANK |
|-----:|---------------|
|     1|               |
|     2|               |
|     3|               |

<br>
seems like I have to have a gap before the next header.
<br>

<details>
<summary>Example of Collapse List</summary>

| Rank | Column 2 |
|-----:|-----------|
|     1| Row 1|
|     2| Row 2|
|     3| Row 3|
</details>


## Week 2 Cloud Assignment
### Service Model Pros and Cons
<br>
<table>
  <caption>Service Models Pros and Cons</caption>
  <br>
  <tr>
    <th></th>  
    <th>Pros</th>
    <th>Cons</th>
  </tr>
  <tr>
    <th>Information As A Service</th>
    <td>
      <ul>
        <li>“Pay only for the amount you consume.”<sup>2</sup></li>
        <li>Stop guessing server capacity.<sup>2</sup></li>
        <li>“Data center investment based on forecast.”<sup>2</sup></li>
        <li>“Scaling on demand.”<sup>2</sup></li>
        <li>“Provides provision processing, storage, networks, and other fundamental computing resources, that the consumer is able to deploy and run arbitrary software.”<sup>1</sup></li>
        <li>Consumer “has control over operating systems, storage, and deployed systems.”<sup>1</sup></li>
        <li>Consumer “possibly limited control of select networking components (e.g. host firewalls).”<sup>1</sup></li>
        <li>Solution are, “flexible, can change more quickly, easily, and cost-effectively than hardware solutions.”<sup>2</sup></li>
        <li>“More control over IT resources.”<sup>2</sup></li>
      </ul>
  </td>
    <td>
      <ul>
        <li>“Consumer does not manage or control the underlying cloud infrastructure.”<sup>1</sup></li>
      </ul>
    </td>
  </tr>
 <tr>
    <th>Platform As A Service</th>
    <td>
      <ul>
        <li>“Pay only for the amount you consume.”<sup>2</sup></li>
        <li>Stop guessing server capacity.<sup>2</sup></li>
        <li>“Data center investment based on forecast.”<sup>2</sup></li>
        <li>“Scaling on demand.”<sup>2</sup></li>
        <li>“Deploy onto the cloud infrastructure consumer-created or acquired systems created using programming languages, libraries, services, and tools supported by the provider.”<sup>1</sup></li>
        <li>“Has control over the deployed systems and possibly configuration settings for the system-hosting environment.”<sup>1</sup></li>        
      </ul>
  </td>
    <td>
      <ul>
        <li>“Consumer does not manage or control the underlying cloud infrastructure including network, servers, operating systems, or storage.”<sup>1</sup></li>
        <li>Can be challenging moving from one vendor to another.</li>
      </ul>
    </td>
  </tr>
<tr>
    <th>Software As A Service</th>
    <td>
      <ul>
        <li>“Pay only for the amount you consume.”<sup>2</sup></li>
        <li>“Data center investment based on forecast.”<sup>2</sup></li>
        <li>Stop guessing server capacity.<sup>2</sup></li>
        <li>“Scaling on demand.”<sup>2</sup></li>
        <li>“Allows the consumer to user the provider’s system running on a cloud infrastructure.”<sup>1</sup></li>
        <li>“Allows clients to access system from various devices through thin client interface, such as a web browser, or a program interface.”<sup>1</sup></li> 
        <li>Manages, “user specific system configuration settings.”<sup>1</sup></li>
      </ul>
  </td>
    <td>
      <ul>
        <li>“The consumer does not manage or control the underlying cloud infrastructure including network, servers, operating systems, storage, or even individual system capabilities. ”<sup>1</sup></li>
        <li>“Less control over IT resources.”<sup>2</sup></li>
        <li>Can have challenges with integrations.</li>
      </ul>
    </td>
  </tr>
<tr><th>1.	Bass, L. and Klein, J., (2022). Deployment and operations for software engineers: A DevOps engineering text. ISBN: 9798801454825</th>
  <th>2. AWS Trating</th>
</tr>
</table>
<br>

### Three different solutions for managing state of services in the cloud

- The service is ***stateful***: The history maintained in the service instance.
- The service is ***stateless***: The history maintained in the client.
- The service is ***stateless***: The history persists outside the service, in the database.

### Application that keeps data of a "count."
<p>
  I'm not sure how to answer this as the two examples in the book are the same, to me, and the only thing is if it is one client or two.  Both clients do the same thing for each variant.
</p>
