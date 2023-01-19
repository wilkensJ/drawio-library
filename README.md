# drawio-library
## How to use this library
Click on [this link](https://app.diagrams.net/?splash=0&libs=0&clibs=Uhttps%3A%2F%2Fraw.githubusercontent.com%2FwilkensJ%2Fdrawio-library%2Fmain%2Flibs%2F1q.xml;Uhttps%3A%2F%2Fraw.githubusercontent.com%2FwilkensJ%2Fdrawio-library%2Fmain%2Flibs%2F2q.xml;Uhttps%3A%2F%2Fraw.githubusercontent.com%2FwilkensJ%2Fdrawio-library%2Fmain%2Flibs%2F3q.xml;Uhttps%3A%2F%2Fraw.githubusercontent.com%2FwilkensJ%2Fdrawio-library%2Fmain%2Flibs%2F4q.xml;Uhttps%3A%2F%2Fraw.githubusercontent.com%2FwilkensJ%2Fdrawio-library%2Fmain%2Flibs%2F5qplus.xml;Uhttps%3A%2F%2Fraw.githubusercontent.com%2FwilkensJ%2Fdrawio-library%2Fmain%2Flibs%2Fclassical.xml) to open a draw.io editor with the preloaded libraries.

There are 5 parts: ``1q``, ``2q``, ``3q``, ``4q``, ``5q+``, ``classical``. 

### Enabling mathematical typesetting

In order to use latex notaion in the circuits and overall in the diagram document, click in the menu bar on Extras -> Mathematical typesetting.

<img width="600" alt="Screenshot_Extras_mathematical_typesetting" src="https://user-images.githubusercontent.com/70592365/213368606-b96c9138-74c8-4dd0-befb-fb28a1fdc375.png">

## Example
In this example a three qubit circuit diagram is put together. 


Drag and drop the wanted initialization gates, here its three. They could be assembled by the single qubit init gates when aligned properly.

<img src="https://user-images.githubusercontent.com/70592365/213367443-57661176-5c1a-4689-97e3-6123558fe276.gif" alt="init gate" width="500"/>



Align the single qubit gate along with the init box, the alignment lines turn solid blue once the right position is met.

<img src="https://user-images.githubusercontent.com/70592365/213368045-c871d0a0-b27d-4253-a894-561fe48834f5.gif" alt="1q gate" width="500"/>


Now the two qubit gate has to be aligned with the initialization and one qubit gate, again, the lines turn solid when it is aligned properly.

<img src="https://user-images.githubusercontent.com/70592365/213369218-c92e6fde-a66c-4b1c-ab19-10f6de3859d8.gif" alt="2q gate" width="500"/>


The CNOT partial gates can be assembled in any way, top-to-down, down-to-top, even a Toffoli gate can be build with the parts in the ``1q`` library.

<img src="https://user-images.githubusercontent.com/70592365/213369561-a934aac7-14fd-424c-aa11-c366e658203b.gif" alt="Toffoli 1" width="500"/>

<img src="https://user-images.githubusercontent.com/70592365/213370040-2abbe10c-cb84-4492-ae07-b25f9ca76048.gif" alt="Toffoli 2" width="500"/>

<img src="https://user-images.githubusercontent.com/70592365/213370229-b479ba2e-b724-4ff2-81e5-f0505bfebec8.gif" alt="Toffoli 3" width="500"/>


There are three different types of measurement boxes, here the one with no connector to the left is chosen to finish the diagram.

<img src="https://user-images.githubusercontent.com/70592365/213370342-23850713-f613-495f-b1fd-92251b26411b.gif" alt="Measurement" width="500"/>


Labeling the diagram parts is possible even with latex notation, double click the box and put two doller signs $$ around the latex part.

<img src="https://user-images.githubusercontent.com/70592365/213371488-c6c10e71-b616-449b-afa8-69ae5bd7b750.gif" alt="Mathematical typesetting" width="500"/>


Diagrams or parts of diagrams can be saved to the personal scratchpad. Select the parts and click the ´´+´´sign next to the scratchpad to save it.

<img src="https://user-images.githubusercontent.com/70592365/213370842-62caa809-e440-4d23-aed4-aceaf1169c22.gif" alt="Save to scratchpad" width="500"/>



