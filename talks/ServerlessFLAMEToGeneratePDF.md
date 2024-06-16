## Topic: Use serverless FLAME to generate PDF

### Context & Problem
- Generating PDFs is a common task in many applications, especially in our domain - F&B, generating PDF invoice is a requirement.
- We're currently using client based pdf export, which runs on user's browser. But once we need to send invoice with email to user, we must generate on server. Here's the problem come. 
- There'are many libraries available to generate PDFs, which we could categorize into 2 groups: chromium based and ghostscript based. We don't go with ghostscript based libraries, as their interfaces are quite in low level. Besides, we're having the HTML template, so convert html2pdf (like wkhtml2pdf) seems is the fastest way. 
- But install chomium to our app overweight. TBA: put the number here. Like obesity in human, an overweight image is not a bad thing, but it leads to many problem like slow start up, more dependencies to maintain, resources to consume... 
- I want to at least isolate the pdf generating service. Sound like microservices are comming. But we're using Elixir, we have another approach to make application distributed. FLAME is one of them. 

### Introduce FLAME

### Trying FLAME on local development

### Trying FLAME on Fly.io

### Further improvements

### Conclusion
