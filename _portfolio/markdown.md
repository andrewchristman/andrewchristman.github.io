---
layout: single
title: "Getting Started With Markdown in 15 Minutes"
og_image: "https://andrewchristman.com/assets/images/og-markdown.png"
classes:
  - markdown-guide
sequence: 2
excerpt: "Beginner quick-start tutorial with examples and guided practice."
---

<div class="notice">
  <p><strong>Project Brief</strong></p>
  <ul>
    <li><strong>Audience:</strong> Non-technical users (spec work).</li>
    <li><strong>User Goal:</strong> To get started using basic Markdown.</li>
    <li><strong>Problem:</strong> Markdown is simple enough to be useful for non-technical users, but the jargon surrounding it can be intimidating.</li>
    <li><strong>Scope:</strong> This guide covers a selection of core Markdown syntax.</li>
    <li>
      <strong>Key Considerations:</strong>
      <ul>
        <li>A visual approach to showing how syntax is rendered aids user comprehension by avoiding jargon and showing results directly.</li>
        <li>Reference-style links are excluded as being too complex for the user goal.</li>
        <li>An example document with multiple different Markdown formatting elements shows Markdown used in practice.</li>
      </ul>
  </li>
    <li><strong>Success Criteria:</strong> The user can demonstrate marking up text with each specified Markdown element.</li>
    <li><strong>Validation:</strong> Test with first-time users against the success criteria.</li>
  </ul>
</div>

## Sample

Markdown is a simple way to format text for display on the web and related applications. You simply write the text you want and then use symbols such as `*` and `_` to tell the computer how you want to display the text. Markdown is widely used across various platforms for tasks such as formatting blog posts, writing messages, and taking notes. This quick-start guide is meant for non-technical users and will show you how to get started with core Markdown formatting in 15 minutes. If you decide to do the exercises, budget up to 30 minutes.

**Note:** 
Markdown comes in different versions, which are called **flavors**. For example, GitHub uses **GitHub Flavored Markdown**. In some cases, you may need or want to take into account the flavor being used. This guide covers core Markdown formatting without examining different flavors.    
{: .notice}

## Headings
You can format headings using hashes `#`. For example:

```markdown
# Heading
```

will show as

{% capture rendered_heading %}
# Heading
{% endcapture %}

<div class="demo-output"> {{ rendered_heading | markdownify }} </div> 

There are six heading levels. Use one hash for the largest size and six hashes for the smallest size. For example, `# Heading` and `###### Heading`.

**Optional Practice:** 
Make a series of headings from one hash to six.
{: .notice}

## Bold and Italic Text

To make text bold, use two asterisks `**` before and after the text. For example:

```markdown
**Bold**
```

will show as

{% capture rendered_bold %}
**Bold**
{% endcapture %}

<div class="demo-output"> {{ rendered_bold | markdownify }} </div> 

To make text italic, use an underscore `_` or single asterisk `*` before and after the text. For example:

```markdown
_Italic_
```

will show as  

{% capture rendered_italic %}
_Italic_
{% endcapture %}

<div class="demo-output"> {{ rendered_italic | markdownify }} </div>

and

```markdown
*Italic*
```

will show as  

{% capture rendered_italic %}
*Italic*
{% endcapture %}

<div class="demo-output"> {{ rendered_italic | markdownify }} </div>

**Optional Practice:** 
Write a sentence with one bold word, one italic word using underscores, and one italic word using single asterisks.
{: .notice}

## Inline Links

Inline links place the link directly in the line of text (hence the name). To insert an inline link, place the desired link text in brackets and place the link URL in parentheses immediately following the brackets. For example:

```markdown
[CommonMark](https://spec.commonmark.org/) is a formal specification for Markdown.
```

will show as 

{% capture rendered_inlinelink %}
[CommonMark](https://spec.commonmark.org/) is a formal specification for Markdown.
{% endcapture %}

<div class="demo-output"> {{ rendered_inlinelink | markdownify }} </div>

Best practice is to use descriptive text such as `CommonMark` rather than generic text such as `Click here` when formatting link text. 

**Optional Practice:** 
Make an inline link with descriptive link text and a URL to a Wikipedia page. 
{: .notice}

## Images

To insert an image, add an exclamation mark followed by alt text in brackets and then the image URL in parentheses. For example:

```markdown
![View from the South Rim of the Grand Canyon](https://upload.wikimedia.org/wikipedia/commons/f/f0/Grand_Canyon_National_Park_-_HCP_-_September_29%2C_2022_-_058_-_Southern_Rim.jpg)
```

will show as

{% capture rendered_image %}
![View from the South Rim of the Grand Canyon](https://upload.wikimedia.org/wikipedia/commons/f/f0/Grand_Canyon_National_Park_-_HCP_-_September_29%2C_2022_-_058_-_Southern_Rim.jpg)
{% endcapture %}

<div class="demo-output"> {{ rendered_image | markdownify }} </div>

Alt text describes the image for screen readers and other assistive devices. While you cannot see the alt text visually, it is still present. 

**Optional Practice:** 
Insert an image using the URL above and relevant alt text.
{: .notice}

## Ordered and Unordered Lists
There are two types of lists: ordered and unordered. Ordered lists have a sequential order (such as 1, 2, 3...), while unordered lists do not. Markdown displays ordered lists using numbers. To make an ordered list, use a number followed by a period before each list item. For example:   

```markdown
1. List Item 1  
2. List Item 2  
``` 

will show as

{% capture rendered_orderedlist %}
1. List Item 1
2. List Item 2
{% endcapture %}

<div class="demo-output"> {{ rendered_orderedlist | markdownify }} </div>

Markdown uses bullet points to display unordered lists. To make an unordered list, use an asterisk or hyphen before each list item. For example:

```markdown
* List Item 1
* List Item 2
```

will show as

{% capture rendered_unorderedlistbullets %}
* List Item 1
* List Item 2
{% endcapture %}

<div class="demo-output"> {{ rendered_unorderedlistbullets | markdownify }} </div>

and

```markdown
- List Item 1
- List Item 2
```

will show as

{% capture rendered_unorderedlisthyphens %}
- List Item 1
- List Item 2
{% endcapture %}

<div class="demo-output"> {{ rendered_unorderedlisthyphens | markdownify }} </div>

**Optional Practice:** 
Make three lists: an ordered list with three items, an unordered list with three items using asterisks, and an unordered list with three items using hyphens. 
{: .notice}

## Code

To display text as inline code, use a single backtick `` ` `` before and after the text. For example:

```markdown
`Code` 
```

will show as

{% capture rendered_code %}
`Code`
{% endcapture %}

<div class="demo-output"> {{ rendered_code | markdownify }} </div>

To display text in a code block, place triple backticks on the line above the text and the line below the text. For example:

````markdown
``` 
Code 
```
````

will show as

{% capture rendered_codeblock %}
``` 
Code 
```
{% endcapture %}

<div class="demo-output"> {{ rendered_codeblock | markdownify }} </div>

Note that the text is now displayed in the darker-colored code block inside the lighter-colored display box. 

**Optional Practice:** 
Write a code sample, real or invented, and enclose it first in single backticks for inline code and then in triple backticks for a code block. 
{: .notice}

## Blockquotes

To format text as a blockquote, use a right angle bracket `>` before the text. For example:

```markdown
Preceding Text  
> Blockquote
```

will show as

{% capture rendered_blockquote %}

Preceding Text  
> Blockquote

{% endcapture %}

<div class="demo-output"> {{ rendered_blockquote | markdownify }} </div>

**Note:**
The appearance of a blockquote can vary depending on the website or application.
{: .notice}

**Optional Practice:** 
Choose a favorite quote, write some comments about it, and then insert the quote as a blockquote inside the comments.
{: .notice}

## Applications
Here are some ways Markdown can be used:
* **Reddit:** You can add Markdown formatting directly to text in the post composer when using the Markdown Editor. 
* **Ghost:** You can use Markdown to format blog posts.
* **Discord:** You can use Markdown to format messages. 
* **Obsidian:** You can store notes as Markdown files.
* **Any Plain-Text Editor:** You can write Markdown in any plain-text editor and then convert it to other formats, such as PDF, with the right tools. 

## Mistakes to Avoid

* Not having a space between the symbol and the text for headings and lists. For example, `#Heading` would be incorrect, while `# Heading` would be correct. 

* Forgetting to close formatting marks. For example, `[link text](URL` would be incorrect, while `[link text](URL)` would be correct. 

* Reversing brackets and parentheses for links. For example, `(Link Text)[URL]` would be incorrect, while `[Link Text](URL)` would be correct. Remember by: **B**rackets for **B**uttons and **P**arentheses for **P**ath. 

## Tips
* Applications vary with respect to supporting Markdown. Use the preview feature, if available, to ensure your Markdown renders correctly.    
* If Markdown is rendering a character that you don't want to render, use a backslash `\` to escape it. For example, `\_Italic\_` will show as `_Italic_` (underscores visible). 
* If an image doesn't display, make sure the path and file name are correct, including spaces and capitalization. 
* Try adding a blank line before and after elements such as headings if the elements don't render correctly. 

## Example

Here is an example of text formatted with Markdown and the rendered result:  

```
# Weekly Project Meeting Notes

## Agenda

1. Status updates
2. Decisions required
3. Risks / blockers
4. Next steps

## Status

* **Installation Guide:** 90% complete
* **Troubleshooting Guide:** Draft ready for review
* **Open Question:** Who should draft the quick start? 

## Decisions

* Sarah will draft the quick start beginning next week. 

## Risks / Blockers

* Two members of the dev team are on vacation, so some details on the quick start may need to wait.

## Next Steps

* Sarah will check with the dev team and report to the product manager. 
```

The rendered result:

{% capture rendered_example %}
# Weekly Project Meeting Notes

## Agenda

1. Status updates
2. Decisions required
3. Risks / blockers
4. Next steps

## Status

* **Installation Guide:** 90% complete
* **Troubleshooting Guide:** Draft ready for review
* **Open Question:** Who should draft the quick start? 

## Decisions

* Sarah will draft the quick start beginning next week. 

## Risks / Blockers

* Two members of the dev team are on vacation, so some details on the quick start may need to wait.

## Next Steps

* Sarah will check with the dev team and report to the product manager. 
{% endcapture %}

<div class="demo-output"> {{ rendered_example | markdownify }} </div>

**Optional Practice:**
Copy-paste the Markdown text above into your editor of choice to see the rendered result. A free editor you can use online is [Dillinger](https://dillinger.io/).
{: .notice}

## Recommended Resources

### Practice Now

* [Dillinger](https://dillinger.io/) allows you to quickly write Markdown online and see the results immediately. 
  
* Selecting the **Markdown Editor** in the [Reddit](https://www.reddit.com/) post composer is an easy way to practice. You first need to [navigate to a community](https://support.reddithelp.com/hc/en-us/articles/28621027395220-How-to-join-or-leave-a-community) and then [create a post/respond to a post](https://support.reddithelp.com/hc/en-us/articles/360060422572-How-do-I-post-and-comment-on-Reddit). Once you are creating or responding to a post, make sure you [select the Markdown Editor](https://support.reddithelp.com/hc/en-us/articles/205191185-How-do-I-format-my-comment-or-post).

### Learn More

* A [Markdown tutorial](https://commonmark.org/help/tutorial/) is available.

* A guide to Markdown by Matt Cone is available in both [PDF format](https://www.markdownguide.org/book/) and [online](https://www.markdownguide.org/getting-started/). Physical copies are also available on [Amazon](https://www.amazon.com/Markdown-Guide-Matt-Cone/dp/B08BW8L1P6/ref=tmm_pap_swatch_0?_encoding=UTF8&qid=&sr=). 

## Final Step
Learning Markdown takes practice. Use one of the resources above to get started. 



