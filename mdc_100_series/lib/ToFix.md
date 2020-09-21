Issues to fix 21-09-20

- Home.dart :
  
  * fixed width and height - in cards Row function _buildGridCards
  Container(
        width: 30,
        height: 30,
        ...

  * fixed number of columns per view - need condition on landscape view or better on screen proportions (tablets, web) 
    body: GridView.count(
          crossAxisCount: 2,