---
title: "Title of this Topic" 
labels: search,keyword,search,keyword
file name: 'file-name-here.md'
path: /docs/path-folder-here/
description: "Use this template with formatting samples to create documentation. Titles should use imperative and title case"
---
Introductory statement explaining the benefit or purpose of the topic. Use this template to add Integration content.

## Objective (H2-level Heading)

Define the reason for completing this topic and list the objectives to complete in this topic.

## Prerequisites

Text introducing unordered list:  

* item  
* item  
* item

Paragraph with **bold** and *italic* text.

Paragraph with inline `/code_sample`. 

Paragraph introducing code sample block (see [code formats](/docs/contribute-documentation#using-code-formats)):

```json
{
  "keys": [
    {
      "kty": "EC",
      "crv": "P-256",
      "use": "sig",
      "kid": "[Key ID]"
      "x": "...",
      "y": "...",
      "d": "..."
    }
  ]
}
``` 

Paragraph with sample hyperlink to [live topic](/reference-docs/login-and-player-access/accessing-github-projects), intended to show hyperlink formatting. 

Paragraph with image to show how images are referenced:

![Splash screen](/static/theme-callouts.png)
_Caption_

Paragraph introducing a video: 

!video[flower.mp4]

Example button:

!riotbutton[Get Started](/docs)

Example table button:

!riotbuttontable[Start here!](/docs)

<!--Title Case, gerunds in most cases -->
### Workflows and Processes (H3-level Heading) 

Text introducing unordered list:  

* item  
* item  
* item

Text introducng ordered list:  

1. Step  
2. Step  
3. Step

#### Block Formats

[[note]]
| **Note:** Something for readers to be aware of: an exception, constraint, dependency, or tip.
| It supports multiline notes with spacing and `code`.

[[important]]
| **Important:** Something manadatory or highly recommended for readers to do or not do, or something to pay close attention to.
| It supports multiline notes with spacing and `code`.

[[warning]]
| **Warning:** Something critical that readers should either definitely do or not do to keep things from breaking. Use this one sparingly.
| It supports multiline notes with spacing and `code`.

[[docs]]
| **See Also:** or **Runbook:** Highlight links to documentation, forms, and downloadable files. Use introduction text like "See Also:", "Runbook:", and such.
| It supports multiline notes with spacing and `code`.

#### Table Examples

Paragraph introducing simple table:

| Column Heading | Column Heading | Column Heading |
| -------------- | -------------- | -------------- |
| Cell | Cell | Cell |
| Cell | Cell | Cell |
| Cell | Cell | Cell |
| Cell | Cell | Cell |

For complex tables, add the `[[format]]` on the line before a markdown table. See the following examples.

Example using `[[linkblock]]`:

[[linkblock]]
| ![](/static/icons/integrate.png) Learn more about integration: | ![](/static/icons/launch.png) Learn more about launch: |  ![](/static/icons/monitoring.png) Learn more about live: |
| -- | -- | -- |
| [Link one](#results) | [Link three](#see-also) | [Link five](#see-also) |
| [Link two](#results) | [Link four](#see-also) | [Link six](#see-also) |

Example using `[[timeline]]`:

[[timeline]]
| ![](/static/icons/integrate.png)<br/>Phase 1 | ![](/static/icons/launch.png)<br/>Phase 2 | ![](/static/icons/monitoring.png)<br/>Phase 3 |
| -- | -- | -- |
| Description of this phase. Rows with links. | Description of this phase. Rows with links. | Description of this phase. Rows with links. |
| [Link](#results) | [Link](#see-also) |  [Link](#see-also) |

Example using `[[timelinerows]]`:

[[timelinerows]]
| ![](/static/icons/integrate.png)<br/>Phase 1 | ![](/static/icons/launch.png)<br/>Phase 2 |  ![](/static/icons/monitoring.png)<br/>Phase 3 |
| -- | -- | -- |
| Description of this phase. Rows with links. | Description of this phase. Rows with links. | Description of this phase. Rows with links. |
| [Link](#results) | [Link](#see-also) |  [Link](#see-also) |

Example using `[[chart]]`:

[[chart]]
| | | Level 1 | Level 2 | Level 3 |
| -- | -- | -- | -- |
| Property 1 | Info | Info | Info |
| Property 2 | Info | Info | Info |

<a name="columns"></a>Example using `[[columns]]`:

[[columns]]
| Step 1 | Step 2 | Step 3 |
| -- | -- | -- |
| Description of this phase. Rows with links. | Description of this phase. Rows with links. | Description of this phase. Rows with links. |
| [Link](#results) | [Link](#results) | [Link](#results) |
| [Link](#results) | [Link](#results) | [Link](#results) |

Example using `[[info]]`:

[[info]]
| Intro | Description |
| -- | -- |
| Build name | Description of the build. |
| Output | Description of the output. |
| Errors | Description of the error. |


## Completion Criteria

Provide the results they should expect when completing these instructions.

## See Also

Add links to integration and reference topics or other websites for more information.

## Next Steps: Name of Topic

Add link to the next step in the series.
