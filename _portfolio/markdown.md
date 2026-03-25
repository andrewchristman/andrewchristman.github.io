---
layout: single
title: "Getting Started With Markdown in 15 Minutes"
---

(in progress)

{: .notice--primary}
**Project Brief**
* Audience: Non-technical users (spec work).
* User Goal: To get started using basic Markdown. 
* Problem: Markdown is simple enough to be useful for non-technical users, but the jargon surrounding it can be intimidating.
* Scope: This guide covers a selection of core Markdown syntax.
* Key Considerations:
    * A visual approach to showing how syntax is rendered aids user comprehension by avoiding jargon and showing results directly. 
    * Reference-style links are excluded as being too complex for the user goal. 
    * An example of a document featuring multiple different Markdown formatting elements is provided so users can see Markdown applied in practice. 
* Success Criteria: The user can demonstrate marking up a document with each specified syntax element. 
* Next Iteration: After evaluating user feedback, revise until 100% of pilot non-technical readers meet the success criteria. 

---

## Sample

Markdown is a simple way to format text for display on the web and related applications. You simply write the text you want and then use symbols such as `**` and `_` to tell the computer how you want to display the text. Markdown and Markdown-like formatting are widely used across various platforms for tasks such as formatting blog posts, writing messages, and taking notes. This quick start guide is meant for non-technical users and will show you how to get started with core Markdown formatting in 15 minutes. If you decide to do the exercises, budget up to 30 minutes.

**Note:** Markdown is best thought of as a family of related formatting languages. Different versions of Markdown are called different **flavors**. There is also **Markdown-like formatting** that shares many features with Markdown but departs from it more substantially. This quick start guide will provide a solid foundation for both Markdown proper and Markdown-like formatting.
{: .notice--primary}

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

There are six heading levels. Use one hash for the largest size and six hashes for the smallest size (for example, `# Heading` and `###### Heading`).

**Optional Practice:** 
Make a series of headings from one hash to six.
{: .notice--primary}

## Bold and Italic Text

To make text bold, use two asterisks `**` before and after the text. For example:

> `**Bold**` will show as  
> **Bold**

To make text italic, use an underscore `_` before and after the text. For example:

> `_Italic_` will show as  
> _Italic_

> **Note:** Asterisks can often, but not always, be used instead of underscores. For example, `*Italic*` will often show as *Italic*. 

> **Optional Practice:** Write a sentence with one **bold** word and one _italic_ word. 

## Inline Links

Inline links place the link directly in the line of text (hence the name). To insert an inline link, place the desired link text in brackets and the link URL in parentheses immediately following the brackets. For example:

> `[CommonMark](https://spec.commonmark.org/) is a widely accepted formal specification for Markdown.` will show as  
> 
> [CommonMark](https://spec.commonmark.org/) is a widely accepted formal specification for Markdown. 

Best practice is to use descriptive text such as `CommonMark` as opposed to `Click Here` when formatting link text. 

> **Optional Practice:** Make an inline link with descriptive link text and a URL to a Wikipedia page. 

## Images

To insert an image, add an exclamation mark followed by alt text in brackets and then the URL in parentheses. For example:

> `![View from the South Rim of the Grand Canyon](https://upload.wikimedia.org/wikipedia/commons/f/f0/Grand_Canyon_National_Park_-_HCP_-_September_29%2C_2022_-_058_-_Southern_Rim.jpg)` will show as
>
> ![View from the South Rim of the Grand Canyon](https://upload.wikimedia.org/wikipedia/commons/f/f0/Grand_Canyon_National_Park_-_HCP_-_September_29%2C_2022_-_058_-_Southern_Rim.jpg)

Alt text describes the image for screen readers and other assistive devices. While you cannot see the alt text visually, it is still present. 

> **Optional Practice:** Insert an image using the URL above and your own alt text. 

## Ordered and Unordered Lists 
There are two types of lists: ordered and unordered. Ordered lists have a sequential order (such as 1, 2, 3...), while unordered lists do not. Markdown displays ordered lists using numbers. To make an ordered list, use a number followed by a period before each list item. For example:   

> ```
> 1. List Item 1  
> 2. List Item 2  
> ``` 
> Will show as
> 1. List Item 1
> 2. List Item 2

Markdown uses bullet points to display an unordered list. To make an unordered list, use an asterisk or hyphen before each list item.  For example:

> ```
> * List Item 1
> * List Item 2
> ```
> Will show as
> * List Item 1
> * List Item 2

> ```
> - List Item 1
> - List Item 2
> ```
> Will show as
> - List Item 1
> - List Item 2

> **Optional Practice:** Make an ordered list with three items and two unordered lists with three items, one with asterisks and one with hyphens.  

## Code

To display text as inline code, use a single backtick `` ` `` before and after the text. For example:

> ``` 
> `Code` 
> ```
> Will show as
>     
> `Code`

To display text in a code block, place triple backticks before and after the text. For example:

>````
>``` 
> Code 
>```
>````
> Will show as
>     
>``` 
> Code 
>```

> **Optional Practice:** Write a code sample, real or invented, and enclose it in single backticks for inline code and triple backticks for a code block. 

## Blockquotes

To separate text as a block quote, use a right angle bracket `>` before the text. For example:

> Preceding Text  
> `> Block Quote`  
> 
> Will show as  
>
> Preceding Text  
> > Block Quote

> **Optional Practice:** Choose a favorite quote, write some commentary on it, and then insert the quote as a blockquote.

## Applications
Here are some ways Markdown can be used:
* **Reddit:** You can add Markdown formatting directly to text in the comment box before posting when using the Markdown Editor. 
* **Ghost:** You can use Markdown to format blog posts.
* **WhatsApp & Discord:** You can use Markdown-like formatting to format messages. 
* **Obsidian:** You can store notes as Markdown files.
* **Any Plain-Text Editor:** You can write Markdown in any plain-text editor and convert into other formats such as PDF with the right tools. 

## Mistakes to Avoid

* Not having a space between the symbol and the text for headings and lists. For example, `#Heading` would be a mistake, while `# Heading` would be correct. 

* Alternating the order of symbols when combining two or more symbols. For example, `**_Text**_` would be a mistake, while `**_Text_**` would be correct. 

* Reversing parentheses and brackets for links. For example, `(Link Text)[URL]` would be incorrect, while `[Link Text](URL)` would be correct. Remember by: **B**rackets for **B**uttons and **P**arentheses for **P**ath. 

## Tips
* Applications vary with respect to supporting Markdown. Use the preview feature, if available, to ensure your Markdown renders correctly. 
* Some editors will convert plain quotes to curly quotes when copy-pasting or typing, which can break code, commands, and URLs. This can lead to unexpected problems when formatting a document. Make sure plain quotes are preserved when copy-pasting and typing.   
* If Markdown is rendering a character that you don't want to render, use a backslash `\` to escape it. For example, `\_Italic\_` will show as `_Italic_` (underscores visible).   
* If an image doesn't display, make sure the path and file name are correct (including spaces and case). 
* If a list doesn't render, add a blank line before the first item.
* For nested lists, indent by 2-4 spaces. Be consistent, as nesting rules can differ across renderers. 

## Example

Here is an example of text formatted with Markdown. Copy-paste this text into your editor of choice to see the rendered result. A free editor you can use online is [Dillinger](https://dillinger.io/).  

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
* **Open Question:** Who should make the quick start? 

## Decisions

* Sarah will draft the quick start starting next week. 

## Risks / Blockers

* Some members of the dev team are on vacation, so some details on the quick start may need to wait.

## Next Steps

* Sarah will check with the dev team and report to the product manager. 
```

## Recommended Resources

### Practice Now

* [Dillinger](https://dillinger.io/) allows you to quickly write Markdown online and see the results immediately. 
  
* Selecting the **Markdown Editor** on the [Reddit](https://www.reddit.com/) post screen is an easy way to practice. You will first need to navigate to a community and then [create a post/respond to a post](https://support.reddithelp.com/hc/en-us/articles/360060422572-How-do-I-post-and-comment-on-Reddit).

### Learn More

* A [Markdown tutorial](https://commonmark.org/help/tutorial/) is available.

* Matt Cone provides a guide to Markdown in both [PDF format](https://www.markdownguide.org/book/) and [online](https://www.markdownguide.org/getting-started/). Physical copies can also be purchased from online retailers like Amazon. 

## Final Step
Learning Markdown takes practice. Use one of the resources above to get started. 





