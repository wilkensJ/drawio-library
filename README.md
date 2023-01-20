
# Quantum Circuit Library


## How to use this library
There are two sizes of the library, big and small, everything but the size is identical. 
<p align="center">
  <img width="400" alt="Big vs small library" src="https://user-images.githubusercontent.com/70592365/213760818-c6d5475e-9204-474a-9b56-881f47a8ef79.png">
</p>

Both have 5 library parts: ``1q``, ``2q``, ``3q``, ``4q``, ``5qplus``, ``classical``.

For the <b> big circuits library </b> click on [this link](https://app.diagrams.net/?splash=0&libs=0&clibs=Uhttps%3A%2F%2Fraw.githubusercontent.com%2FwilkensJ%2Fdrawio-library%2Fmain%2FlibsL%2F1qL.xml;Uhttps%3A%2F%2Fraw.githubusercontent.com%2FwilkensJ%2Fdrawio-library%2Fmain%2FlibsL%2F2qL.xml;Uhttps%3A%2F%2Fraw.githubusercontent.com%2FwilkensJ%2Fdrawio-library%2Fmain%2FlibsL%2F3qL.xml;Uhttps%3A%2F%2Fraw.githubusercontent.com%2FwilkensJ%2Fdrawio-library%2Fmain%2FlibsL%2F4qL.xml;Uhttps%3A%2F%2Fraw.githubusercontent.com%2FwilkensJ%2Fdrawio-library%2Fmain%2FlibsL%2F5qplusL.xml;Uhttps%3A%2F%2Fraw.githubusercontent.com%2FwilkensJ%2Fdrawio-library%2Fmain%2FlibsL%2FclassicalL.xml) to open a draw.io editor with the preloaded L libraries.

For the <b> small circuits library </b> click on [this link](https://app.diagrams.net/?splash=0&libs=0&clibs=Uhttps%3A%2F%2Fraw.githubusercontent.com%2FwilkensJ%2Fdrawio-library%2Fmain%2FlibsS%2F1qS.xml;Uhttps%3A%2F%2Fraw.githubusercontent.com%2FwilkensJ%2Fdrawio-library%2Fmain%2FlibsS%2F2qS.xml;Uhttps%3A%2F%2Fraw.githubusercontent.com%2FwilkensJ%2Fdrawio-library%2Fmain%2FlibsS%2F3qS.xml;Uhttps%3A%2F%2Fraw.githubusercontent.com%2FwilkensJ%2Fdrawio-library%2Fmain%2FlibsS%2F4qS.xml;Uhttps%3A%2F%2Fraw.githubusercontent.com%2FwilkensJ%2Fdrawio-library%2Fmain%2FlibsS%2F5qplusS.xml;Uhttps%3A%2F%2Fraw.githubusercontent.com%2FwilkensJ%2Fdrawio-library%2Fmain%2FlibsS%2FclassicalS.xml) to open a draw.io editor with the preloaded S libraries.




Please cite this repository using the right panel or with the ``CITATION.cff`` file when used in any kind of publication.

  Enabling mathematical typesetting  |  Zoom
:-------------------------:|:-------------------------:
In order to use latex notaion in the circuits and overall in the diagram document, click in the menu bar on Extras -> Mathematical typesetting. | Use the zoom function by clicking on the magnifier under the menu bar. |
<img width="400" alt="Screenshot_Extras_mathematical_typesetting" src="https://user-images.githubusercontent.com/70592365/213368606-b96c9138-74c8-4dd0-befb-fb28a1fdc375.png"> | <img width="420" alt="Zoom" src="https://user-images.githubusercontent.com/70592365/213519090-28fca2d9-99b1-4520-be21-5dc6299e1ad6.gif">

Save to file  |  Load other libraries
:-------------------------:|:-------------------------:
Select ``File``-> ``Export as`` and choose a format. With the .png format a border width can be defined. | When other forms are needed like dashed rectangles, load other libraries with ``+ More Shapes`` option under the existing libraries. |
<img width="400" alt="Bildschirmfoto 2023-01-19 um 21 52 27" src="https://user-images.githubusercontent.com/70592365/213525510-95255261-de82-4b24-ae4d-e597461a6c45.png"> | <img width="400" alt="Bildschirmfoto 2023-01-19 um 22 07 17" src="https://user-images.githubusercontent.com/70592365/213525566-b7ac4a83-aaf1-46a3-867d-60efb17d6222.png">




## Example
In this example, illustrated with short gifs, a three qubit circuit diagram is put together, saved to the scratchpad and loaded from it.

  Prebuild 3 qubits initializaion             |  By hand 3 qubits initializaion
:-------------------------:|:-------------------------:
Drag and drop the wanted initialization gates, here its three. | They could be assembled by the single qubit init gates when aligned properly. |
<img src="https://user-images.githubusercontent.com/70592365/213367443-57661176-5c1a-4689-97e3-6123558fe276.gif" alt="init gate" width="400"/> | <img src="https://user-images.githubusercontent.com/70592365/213514566-c440fa9e-966f-4345-8372-984f5108f859.gif" alt="init gate" width="400"/>


  Single qubit gate             |  Two qubit gate
:-------------------------:|:-------------------------:
 Align the single qubit gate along with the init box, the alignment lines turn solid blue once the right position is met. | Now the two qubit gate has to be aligned with the initialization and one qubit gate, again, the lines turn solid when it is aligned properly.|
<img src="https://user-images.githubusercontent.com/70592365/213368045-c871d0a0-b27d-4253-a894-561fe48834f5.gif" alt="1q gate" width="400"/>  |  <img src="https://user-images.githubusercontent.com/70592365/213369218-c92e6fde-a66c-4b1c-ab19-10f6de3859d8.gif" alt="2q gate" width="400"/>


Toffoli Top             |  Toffoli Middle          | Toffoli Bottom
:-------------------------:|:-------------------------:|:-------------------------:|
<img src="https://user-images.githubusercontent.com/70592365/213369561-a934aac7-14fd-424c-aa11-c366e658203b.gif" alt="Toffoli 1" width="250"/> | <img src="https://user-images.githubusercontent.com/70592365/213370040-2abbe10c-cb84-4492-ae07-b25f9ca76048.gif" alt="Toffoli 2" width="250"/> | <img src="https://user-images.githubusercontent.com/70592365/213370229-b479ba2e-b724-4ff2-81e5-f0505bfebec8.gif" alt="Toffoli 3" width="250"/> |


 Measurement             |  Mathematical labeling 
:-------------------------:|:-------------------------:
There are three different types of measurement boxes, here the one with no connector to the left is chosen to finish the diagram. | Labeling the diagram parts is possible even with latex notation, double click the box and put two doller signs $$ around the latex part.|
<img src="https://user-images.githubusercontent.com/70592365/213370342-23850713-f613-495f-b1fd-92251b26411b.gif" alt="Measurement" width="400"/> | <img src="https://user-images.githubusercontent.com/70592365/213371488-c6c10e71-b616-449b-afa8-69ae5bd7b750.gif" alt="Mathematical typesetting" width="400"/> 


 Save to Scratchpad             |  Load from Scratchpad 
:-------------------------:|:-------------------------:
Diagrams or parts of diagrams can be saved to the personal scratchpad. Select the parts and click the ``+`` sign next to the scratchpad to save it. | When clicking on the diagram in the scratchpad, the whole saved diagram appears again. |
<img src="https://user-images.githubusercontent.com/70592365/213370842-62caa809-e440-4d23-aed4-aceaf1169c22.gif" alt="Save to scratchpad" width="400"/> | <img src="https://user-images.githubusercontent.com/70592365/213509058-113cce28-ae3f-4d59-a477-f4e16b53366d.gif" alt="Load from scratchpad" width="400"/>




