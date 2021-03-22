# QA-Automation-Backend

## How to run
<br>

### - Basic analysis

<code>
newman run ./qa_workshop.json -e QA.postman_environment.json
</code>

<br>
<br>
<br>

### - HTML analysis

<code>
newman run ./qa_workshop.json -e QA.postman_environment.json --reporter-htmlextra-export ./reports/report.html

</code>