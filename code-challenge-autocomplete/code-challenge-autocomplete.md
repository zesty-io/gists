# Code Challenge: Autocomplete Service

> Create a web service using Golang that can return autocomplete sugestions based on word fragments, using a local text file as the data source.


## Service Requirements
- Web service which can be requested over http
  - e.g. http://localhost:9000/autocomplete?term=th
- Results should be ordered by word frequencey (most frequent first)
- Results should be limited to top 25
- Ignore non-word entities (e.g. Numbers)
- You must use pure Go - no third-party libraries, data stores, etc. This includes the web server.
  - *However, feel free to use any reference resources, just make sure to cite anything you use (aside from the obvious godocs, etc).*

## Challenge Requirements
- Use the provided complete works of Shakespeare as the local web server data source
- Include a document of your results for the following fragments: th, fr, pi, sh, wu, ar, il, ne, se, pl
- Include a document on to start the web service and an example cURL request
- Provide a access to your solution with documentation via a url

### Additional Notes
- This challenge isn't timed but please don't spend more than a few hours on it as we don't want to take up too much of your time.
- There are various decisions and minor differences that go into a solution. We'll be evaluating your solution based on your approach to the problem (algorithm), readability/maintainability/style, and performance characteristics. Only include any tests if it helps you, we won't judge based on their presence or absence.
