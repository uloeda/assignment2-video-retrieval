# Interactive video retrieval

Given a still image or a description, the goal is to find the shot where the action happens. Each result identifies a video and a time range so the person searching can play the segment and check the match.

## Practice search

Can you find the red bus as it passes the grey buildings? The image on the left was the query. The animation on the right shows the first result from a search across six shots in three original practice videos.

| Query frame | Retrieved shot |
| --- | --- |
| ![A red bus in front of grey buildings](preview/query-frame.jpg) | ![Two-second loop of the red bus driving past the buildings](preview/matched-shot.gif) |

The top match was **video `00042`, shot 2**, from **2,000 to 4,000 milliseconds**. The still frame captures the bus in one position. Playing the result shows it moving through the scene.

## Search tasks

- **Visual known-item search (KIS-V)** — watch a clip and find the corresponding shot.
- **Textual known-item search (KIS-T)** — find a particular shot from a written description.
- **Ad-hoc video search (AVS)** — find several distinct shots that satisfy a request.
