---
templateKey: blog-post
name: Tooltip
eng-name: UITooltip
status: Implemented
category: Popovers
component-illustration: ""
screenshot: https://uploads-ssl.webflow.com/5cf94933bf4ff12103d58c2a/5d091dd6cab7486074601273_image_preview-63.png
styles: some styles
using-component: >-
  Tooltips are used to display clarifying labels or details when hovering over
  another element. Common uses include text labels for icon actions, and
  explanations of other UI elements. 


  # **Content**


  Only text content can be placed within tooltips. Avoid text longer than 100 characters. 


  # **Alternatives**


  Tooltips should not be used to display truncation, nor can they contain interactive elements. Use a [UIPeek](/ui-components/peeks) for those cases. If you want to combine a tooltip with an information icon, use the [UIProtip](/ui-components/protips) component. For more details on when to use each component, see the [Tooltips vs. Peeks](/learn/tooltips-peeks) learn Fabric module.
structure-img: https://uploads-ssl.webflow.com/5cf94933bf4ff12103d58c2a/5d6ec3a644910848309051c2_Tooltip%20-%202%402x.png
structure: >-
  # 1. Content Area


  Most of a tooltip is dedicated to the rectangular text content area. The width of the content area should be responsive to the text of the tooltip, but the full width should not exceed 180px in most cases. 


  # 2. Pointer


  Tooltips always point to their triggering element. Pointers are placed in the middle of one of the tooltip’s four sides.
behavior: >-
  Tooltips themselves are non-interactive. They appear as a result of hover
  interactions with other components. Tooltip content can’t be highlighted &
  copied, unlike Peeks. 




  # **Timing**


  Tooltips should most often appear after long hover (500ms) over the triggering element. In rare circumstances, tooltips may appear immediately on hover, but this should be avoided. 


  Tooltips should be dismissed immediately when moving the cursor off of the triggering element. 




  # **Placement**


  Because tooltips extend beyond the bounds of the triggering element, be sure that placement of the tooltip will not cause it to appear outside the bounds of the page window.
date: 2021-04-14T16:59:32.726Z
---
