# CellPin
This application offer two functions. <br/>
    - classifies whether cells in the given image(X100 magnification) are CPE or No CPE. <br/>
    - calculates the TCID50 by entering the following variables.

## How to work (Click on image.)

[![CellPin 팀 웹페이지 시연영상](https://img.youtube.com/vi/yzHPEwOc6MA/0.jpg)](https://youtu.be/yzHPEwOc6MA&t=0s)

## Contribution
CellPin Team building
1. [Hyeseong Lee](https://github.com/orgs/CellPin/people/gotjd709)
    - Main: DataLabeling, DataPreprocessing
2. [Donghun lee](https://github.com/orgs/CellPin/people/Soah-1994)
    - Main: ModelArchitecture, Sub: TCID50Calculator
3. [Kipyo Ryu](https://github.com/orgs/CellPin/people/fbrlvy87)
    - Main: Augmentation, TCID50Calculator, Sub: ModelArchitecture
4. [Jonghoon Park](https://github.com/orgs/CellPin/people/Zion-J-Park)
    - Main: BackEnd
5. [Jeongwoo Kim](https://github.com/orgs/CellPin/people/mochafreddo)
    - Sub: BackEnd

## Acknowledgement
Data Contribution: Virology Lab(Hye Kwon Kim, D.V.M., Ph. D. Assistant Professor), Department of Microbiology, College of Natural Science, Chungbuk National University

## How to install thru Docker
```sh
docker build -t zionjpark5993/cellpin:cellpin .
```

## How to run thru Docker
```sh
docker run -p 80:80 zionjpark5993/cellpin:cellpin
```

## Reference
- Wang, Ting-En et al. “Differentiation of Cytopathic Effects (CPE) induced by influenza virus infection using deep Convolutional Neural Networks (CNN).” PLoS computational biology vol. 16,5 e1007883. 13 May. 2020, doi:10.1371/journal.pcbi.1007883
