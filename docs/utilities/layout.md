---
layout: default
title: Upload a File to D2L
parent: Activities
---

# Layout Utilities
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

To upload a file to a submission:
1. Navigate to Assignments in the Activities drop down menu in your class.
   Here you will find a list of assignments for your course. These are the sections you will find.
    ![assignments navigation row](https://user-images.githubusercontent.com/24902962/114898253-c9d1fe00-9dc6-11eb-88fe-caa5c763a759.png)
    - Folder: provides a link to the specific assignment and for some instructors, required documents for that assignment.
    - Completion Status: indicates whether or not you have submitted the assignment. Values are either "Not Submitted" or "*x* Submission, *n* File(s)".
    - Score: the assignment's grade, initially 0.
    - Due Date: date when the assignment must be submitted by.
2. Navigate to the link in the Folder section. This is where you will find the Submit Assignment section.
   ![image](https://user-images.githubusercontent.com/24902962/114899502-ddca2f80-9dc7-11eb-9d78-9d65e140db2b.png)
4. Click on the Add a File button.
5. A pop up will appear that will give you options from where you would like to upload your assignment from. *I have not once used anything other than My Computer".
6. Click on My Computer.
7. Click on Upload.
8. Find your file on your device. *This is where the pro tip comes in handy, especially when you're uploading files for quizzes because these uploads are time sensitive*.
9. Once found, select the file and click open. This will return you to step 7. If necessary, repeat the steps to upload multiple files or you can select them all at once by holding Command (Mac) or Control (Windows) and click the necessary files.
10. Once all files are uploaded click Add. This will upload your assignments to your submission but not submit them.

Double check that the correct amount of files have been uploaded.

![correctly uploaded files](https://user-images.githubusercontent.com/24902962/114902390-a0b36c80-9dca-11eb-893e-1c112d704aa7.png)
In this image I have uploaded 1 file. If you have uploaded multiple files the 1 will represent the number of files you have uploaded.

Another way to double check your submission was successful is navigate back to the Assignments page and check the assignment's Completion Status column. The number of files and submissions should have updated.

D2L will also send a submission receipt to your bcit email. 

These spacers are available to use for margins and padding with responsive utility classes. Combine these prefixes with a screen size and spacing scale to use them responsively.
---

| Classname prefix | What it does                  |
|:-----------------|:------------------------------|
| `.m-`            | `margin`                      |
| `.mx-`           | `margin-left`, `margin-right` |
| `.my-`           | `margin top`, `margin bottom` |
| `.mt-`           | `margin-top`                  |
| `.mr-`           | `margin-right`                |
| `.mb-`           | `margin-bottom`               |
| `.ml-`           | `margin-left`                 |

| Classname prefix | What it does                    |
|:-----------------|:--------------------------------|
| `.p-`            | `padding`                       |
| `.px-`           | `padding-left`, `padding-right` |
| `.py-`           | `padding top`, `padding bottom` |
| `.pt-`           | `padding-top`                   |
| `.pr-`           | `padding-right`                 |
| `.pb-`           | `padding-bottom`                |
| `.pl-`           | `padding-left`                  |

Spacing values are based on a `1rem = 16px` spacing scale, broken down into these units:

| Spacer/suffix  | Size in rems  | Rem converted to px |
|:---------------|:--------------|:--------------------|
| `1`            | 0.25rem       | 4px                 |
| `2`            | 0.5rem        | 8px                 |
| `3`            | 0.75rem       | 12px                |
| `4`            | 1rem          | 16px                |
| `5`            | 1.5rem        | 24px                |
| `6`            | 2rem          | 32px                |
| `7`            | 2.5rem        | 40px                |
| `8`            | 3rem          | 48px                |
| `auto`         | auto          | auto                |

Use `mx-auto` to horizontally center elements.

#### Examples
{: .no_toc }

In Markdown, use the `{: }` wrapper to apply custom classes:

```markdown
This paragraph will have a margin bottom of 1rem/16px at large screens.
{: .mb-lg-4 }

This paragraph will have 2rem/32px of padding on the right and left at all screen sizes.
{: .px-6 }
```

## Horizontal Alignment

| Classname               | What it does                     |
|:------------------------|:---------------------------------|
| `.float-left`           | `float: left`                    |
| `.float-right`          | `float: right`                   |
| `.flex-justify-start`   | `justify-content: flex-start`    |
| `.flex-justify-end`     | `justify-content: flex-end`      |
| `.flex-justify-between` | `justify-content: space-between` |
| `.flex-justify-around`  | `justify-content: space-around`  |

_Note: any of the `flex-` classes must be used on a parent element that has `d-flex` applied to it._

## Vertical Alignment

| Classname              | What it does                    |
|:-----------------------|:--------------------------------|
| `.v-align-baseline`    | `vertical-align: baseline`      |
| `.v-align-bottom`      | `vertical-align: bottom`        |
| `.v-align-middle`      | `vertical-align: middle`        |
| `.v-align-text-bottom` | `vertical-align: text-bottom`   |
| `.v-align-text-top`    | `vertical-align: text-top`      |
| `.v-align-top`         | `vertical-align: top`           |

## Display

Display classes aid in adapting the layout of the elements on a page:

| Class             |                         |
|:------------------|:------------------------|
| `.d-block`        | `display: block`        |
| `.d-flex`         | `display: flex`         |
| `.d-inline`       | `display: inline`       |
| `.d-inline-block` | `display: inline-block` |
| `.d-none`         | `display: none`         |

Use these classes in conjunction with the responsive modifiers.

#### Examples
{: .no_toc }

In Markdown, use the `{: }` wrapper to apply custom classes:

```markdown
This button will be hidden until medium screen sizes:

[ A button ](#url)
{: .d-none .d-md-inline-block }

These headings will be `inline-block`:

### heading 3
{: .d-inline-block }

### heading 3
{: .d-inline-block }
```
