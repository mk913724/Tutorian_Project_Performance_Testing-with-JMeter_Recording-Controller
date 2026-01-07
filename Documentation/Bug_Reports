## **Bug Report**

### **Bug Report 1**

**Bug ID:** PERF-001
**Title:** Home Page shows high response time under normal load
**Category:** Performance

**Severity:** High
**Priority:** High

### **Environment**

* **Application:** Tutorian
* **Test Tool:** Apache JMeter
* **Request Type:** HTTP GET
* **Controller:** Recording Controller

### **Description**

During performance testing, the Home Page exhibited high response time even under minimal load conditions. Multiple HTTP requests exceeded the acceptable response time threshold.

### **Steps to Reproduce**

1. Open Apache JMeter
2. Execute the recorded HTTP request for the Home Page
3. Run the test using the default Thread Group
4. Observe response time in *View Results Tree* or *Summary Report*

### **Expected Result**

* Home Page should load within **≤ 3 seconds**
* No warning status should be displayed

### **Actual Result**

* Response time exceeded **3–5 seconds**
* Some samplers were marked as **Warning**
* Large response size was observed

### **Impact**

* Poor user experience on initial page load
* Increased risk of user bounce rate

---

### **Bug Report 2**

**Bug ID:** FUNC-002
**Title:** Terms & Conditions page shows warning status during performance test
**Category:** Functional / Performance

**Severity:** Medium
**Priority:** Medium

### **Environment**

* **Application:** Tutorian
* **Test Tool:** Apache JMeter
* **Request Type:** HTTP GET

### **Description**

During performance testing, the Terms & Conditions page returned a Warning status, indicating unstable response behavior under repeated HTTP requests.

### **Steps to Reproduce**

1. Add the Terms & Conditions page URL in an HTTP Request sampler
2. Execute the test using recorded navigation
3. Review sampler results in JMeter listeners

### **Expected Result**

* Page should respond consistently
* No warning or response delay should occur

### **Actual Result**

* Warning status observed
* Response time fluctuated across multiple requests

### **Impact**

* Indicates possible backend or server inefficiency
* May result in inconsistent page loading for users

---

### **Bug Report 3**

**Bug ID:** PERF-003
**Title:** Refund Policy page has very high response time and warning status
**Category:** Performance

**Severity:** High
**Priority:** High

### **Environment**

* **Application:** Tutorian
* **Test Tool:** Apache JMeter
* **Request Type:** HTTP GET

### **Description**

The Refund Policy page demonstrated significantly high response time along with multiple Warning statuses during performance test execution.

### **Steps to Reproduce**

1. Execute the HTTP request for the Refund Policy page
2. Run the test under sequential load conditions
3. Analyze results using the Summary Report

### **Expected Result**

* Page should load within acceptable response time limits
* No warning status should be present

### **Actual Result**

* Response time exceeded the defined threshold
* Warning status detected repeatedly

### **Impact**

* Critical legal information page loads slowly
* Potential trust, usability, and compliance risks

