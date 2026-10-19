# The Discovery Room

A static website for grades 9–10 with 12 clickable notebooks, animated GIFs, the worksheet's exact practice scenarios, and Step / Why? responses. No warm-up, notes activity, or summaries are included.

Open index.html locally or serve the folder with any static web server. For GitHub Pages, publish the folder's contents on a configured Pages branch, or place the folder under an existing Pages site without replacing its files.

Student work is saved in local browser storage. Downloads are genuine Word .docx files created locally without an external library. Shared devices include a clear-work option after submission.

Students download their Word document and attach it to their Google Classroom assignment. No email configuration or sending account is required.

## Scientific method terminology

The requested posters use Ask a question, Research, Hypothesis, Experiment, Analyze data, Conclusion. The supplied worksheet instead includes Share results in place of Analyze data. The Poster and Slideshow examples depict sharing results. The website intentionally leaves student step responses as free text, so they may write Share results even with the requested six reference posters. No automatic grading is applied.

To change the reference posters and footer labels, edit method in config.js:
- requested: the user's requested six
- worksheet: the worksheet's six (includes Share results)
- seven: all seven steps

## Files

index.html, style.css, app.js, config.js, data.js, and assets/ are the website. No student responses are stored in GitHub.
