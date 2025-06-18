<h1>
  <span class="headline">AI Use Case: Marketing Analytics</span>
  <span class="subhead">Leveraging GenAI for unstructured marketing data insights</span>
</h1>

**Learning objective:** Use GenAI tools to synthesize insights from unstructured marketing data, such as social media comments, NPS feedback, and survey responses.

## Get right to the insights

You're working with 1,000 open-ended customer comments—some glowing, some frustrated, and many somewhere in between.

Reading and sorting them all yourself would take hours. Instead, let’s walk through how to apply GenAI to extract themes, summarize sentiment, and surface unexpected insights.

Let's practice with some small sample dataset:
- [sample_comments_feedback.csv](assets/sample_comments_feedback.csv)
- [sample_nps_feedback.csv](assets/sample_nps_feedback.csv)

---

## Analyze social media feedback fast

**Scenario:** You’re handed a CSV file of 40 comments about your latest product launch. Your stakeholders want to know how people feel and what they’re talking about.

### Step 1: Clean and prep the file

* Open the spreadsheet or CSV
* Remove irrelevant rows, spam, and duplicates
* Make sure comments are in a single column with a clear header (e.g., `comment`)

### Step 2: Use a structured prompt

**Prompt example:**

```
Attached is a CSV file with 40 tweets about our new product launch. Each row has a single tweet in the column labeled "tweet_text."

Please:
- Label each tweet as positive, negative, or neutral
- List the top three recurring topics
- Summarize the overall sentiment in one sentence
```

If the tool doesn’t support file upload, copy/paste a sample of 10–20 rows as plain text.

### Step 3: Review and refine

Check that:

* Sentiment labels make sense
* Topics reflect what you expected, or didn’t expect!
* The summary is useful and clear

> ⚠ GenAI can,  and will, misread sarcasm, slang, or brand-specific tone. Always review the output.

---

## Tackle NPS feedback the same way. Let's try it:

## Tips for prepping your input

> 🏆 Your job is to first prep, then prompt. Clean inputs lead to sharper insights!

* **Remove spam, duplicates, and sensitive data**
* **Make sure your column headers are clear and descriptive**
* **Be specific in your ask. What should GenAI return and in what format?**

**Prompt example:**

```
Attached is a CSV of 40 NPS comments from customers. Each comment is in a column labeled "comment_text."

Please:
- List 3 positive themes
- List 3 areas for improvement
- Highlight any surprising comments
- Summarize overall sentiment in one sentence
```

---

## Guiding questions

* What patterns or themes do you notice right away?
* Which responses feel most representative of the group? Which feel like outliers?
* Are any key topics missing from GenAI's summary that you expected to see?
* If you had to group this feedback for a stakeholder report, what headings would you use?

## Reflection prompts

* How confident do you feel in the themes GenAI identified? Why?
* Where did your business context help you interpret or refine the AI's output?
* If you reused this prompt on a different dataset, what would you change?
* What additional questions could you ask GenAI to deepen your insight?

> 💬 Share one takeaway or surprising pattern from your NPS analysis with a peer or in the class discussion.
