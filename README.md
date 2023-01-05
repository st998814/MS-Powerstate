# MS-Powerstate data analytics

## About

### The open source project for checking Windows OS system automatically.


Microsoft Windows platform can check power state details such as status (sleep, power-off, hibernation), duration time, SW/HW drip...etc.

Although we can investigate issues from MS sleep-study reports, this task can automatically deal with multiple devices simultaneously and effortlessly.

Failing criteria depend on different inspection standards, or you can refer to failing creteria.xls.


## Method&Tools

### Getting raw data 

* Regular expression - Filtering strings.
```sh
re.compile(r"var LocalSprData = (.*?);$",re.MULTILINE | re.DOTALL)
```
* Json object - store and orgnized as list.

### Parsing

* Python class structure - Fill in data.

### Identify issue

Follow the guide of failing crrteria to find out issues.

### Generating excel report 

* Pandas - For basic structure 
          
* openxyl- For detail adjustment












