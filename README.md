# MA615-HW4-Text-mining

## Text Analysis: An INDIVIDUAL Assignment

In this section of the course, we have barely scratched the surface of the complex field of text analysis. While working on this text analysis assignment, consider some of the basic points discussed in class.
Organization of text in documents enables document analysis. However, the organization may also be a constraint. Silge and Robinson's Text Mining with R demonstrates various document analysis methods based on single-word tokenization. The results are impressive, considering that single-word tokenization ignores sentences, paragraphs, headings, and other document features authors use to communicate clearly through documents.
The Truenumbers package offers an alternative approach to organizing document text, tokenizing sentences and paragraphs. Simply retaining paragraph and sentence boundary information extends the analytic possibilities, but Truenumbers offers other features to track, group and subset data items. Using the tagging feature of Truenumbers provides a way to track theme-related terms and mark passages where action, emotional responses, or other key events occur. New Truenumbers can be made to record statistics and other derived measures.

### Task ONE: Pick a book

Begin by picking a fiction book. Choose wisely. The Gutenberg Project Gutenberg project is not the only source, but a convenient one. You will most likely end up using David Robinson’s gutenbergr package.
A book organized by chapters, paragraphs, and sentences will make things easier, as will the availability of a short synopsis. Pick any book written in or translated to English. Books mentioned in Text Mining with R are not allowed, but the authors of the books mentioned are.
Every student must select a unique book. Use this spreadsheet to note and record book choices, so that there are no book duplicates.

### Task TWO: bag of words analysis

As shown in Chapter 2 of Text Mining with R do a sentiment display through the narrative of your book. You should choose an index length and a sentiment dictionary that gives you the best fit between the plotline of the book and the graph that you create. If you don’t know the plot line of the book, you will need to either skim or refer to a synopsis.

### Task THREE: sentence-level analysis

Truenumbers provides data organization and tools that can be used for text analysis. To get started, use the ingestion function in Book2TN-v3.R load your book into a number space. The example that is included with this assignment provides working code that shows how to use Book2TN-v3.R.
Now, with the book tokenized by sentence, paragraph, and chapter, use functions from the tnum package for the three text analysis tasks below.
Use the sentimentr package to produce a sentence level sentiment analysis of your book. See Sentiment analysis in r with sentimentr. Compare this analysis with the analysis you did in Task TWO. Can you make adjustments so that the two analyses are comparable?
Pick two characters from your book. Use tags to track the characters individually as their names appear in paragraphs. Create truenumbers for the number of times each character appears in each chapter and the number of times both characters appear in the same paragraphs.
Use character tracking and other data from truenumbers tp produce visualizations of the characters' story lines through the book.
Note: I will post example code and other information related to TaskThree as soon as possible. Please ask questions about Task THREE. This question is purposely experimental. Your feedback would be appreciated. Thanks.
