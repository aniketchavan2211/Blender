## Geometry Nodes

<img width="868" alt="{BF35511F-F7C0-4A48-BBEB-FDC5CEC5F58B}" src="https://github.com/user-attachments/assets/df28f1de-151b-4e5f-a610-9f52eb8b6cda">

Select Geometry Nodes tab in Header Region,

click on New, this will create new geometry node, geometry node is a modifiers. 

in empty space below click `Shift+A` key, then click `Points` > `distribute points on faces`

<img width="639" alt="{522B85CC-88AD-44E6-A7F2-E448A1EC5D26}" src="https://github.com/user-attachments/assets/13e3f2ab-0341-4b7a-8529-a728f2c0503c">


Join Geometry because of icing disappear, and points are only seen.

<img width="805" alt="{DD669BF4-2BA0-405F-85A0-F1BC13D98053}" src="https://github.com/user-attachments/assets/ca05f6af-ede2-4d48-9ef5-2f042ebcdb35">

<img width="776" alt="{7FCD38D8-F69A-4084-993F-27F9161371DB}" src="https://github.com/user-attachments/assets/9f45dcdb-b1be-40d6-8eda-725927dc0293">

Connect `Group Input` Geometry Node to `Join Geometry` Geometry Node

<img width="597" alt="{F2576DFA-4101-4B40-83EE-C0E699295806}" src="https://github.com/user-attachments/assets/4ed662aa-7f03-4f2c-9564-6ea7f9a1c837">


the Goemetry Node appear only on Icing ,if other object is selected then geometry nodes will disappear and appear if we selecr icing again, to keep 
geometry nodes on screen click on pin.

<img width="730" alt="{76E902D0-ABE7-4FAF-AA8B-40602640E2ED}" src="https://github.com/user-attachments/assets/5a768fda-e444-4f8f-a4ed-d93decc05df0">


Drag sphere from collection to geometry node below tab, it will turn into Object Info Box

<img width="828" alt="{75928FB6-37FD-4FB9-AADB-A74EDD537A42}" src="https://github.com/user-attachments/assets/7640b263-c91c-4356-99ab-27e73e24b19e">

then Add new Node, click `Shift+A` Instances > Instance on Points

<img width="774" alt="{058F6948-E689-4D75-80F8-23854030B1ED}" src="https://github.com/user-attachments/assets/44aa7ebf-abd6-423b-b224-0758f5ee136f">


connect `Object Info` Geometry Node to `Instance on Points` Instance Node and Distribute Points on faces Points Node to Instances on points Points Node 

<img width="688" alt="{16B120C7-4E76-487E-B2DA-3AD3A76B5780}" src="https://github.com/user-attachments/assets/c292cf85-6f16-4a55-88cb-0481d57395e5">

Sphere colliding to each to stop it, in Distribute Points on faces select Poisson disk not Random.

sphere here acts as sprinkes on donut, 

sphere also appear on under neat icing ,so stop wasting resouces on things we can see in render, but use CPU for it, we will switch to Weight Mode 

<img width="664" alt="{13A3357E-39D8-4F40-A358-1684BA7BD673}" src="https://github.com/user-attachments/assets/8eb821ae-09f9-4f83-b8ca-e3dcfbb23914">

In Data create a group named `sprinkle_density`

<img width="841" alt="{DB5CA2B9-4D8C-41AF-8B1B-3487836C3ACE}" src="https://github.com/user-attachments/assets/a80bed80-fb1e-4eab-869d-4f149e62621f">

adjust to real world size by select all object draging, and use `S` key move cursor

adjust sprinkle densirty by Math function Node 


<img width="952" alt="{355FB74A-BF47-49B7-9D77-B6635D68C021}" src="https://github.com/user-attachments/assets/82f5c0d4-35cc-490c-8b0b-3167d151dfe5">

Final Output: Sprinkle 01

<img width="960" alt="{D36B1336-0152-4608-8D5E-0E0200B3E0DB}" src="https://github.com/user-attachments/assets/41d54e09-f300-4d33-badc-d6e7fd41ea51">
