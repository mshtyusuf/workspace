<h>SHRINE APP</h>

Issues to fix 21-09-20

- Home.dart :
  
  * Width and height depend on view, use proportions - in cards Row function _buildGridCards
  Container(
        width: 30,
        height: 30,
        ...

  *  Number of columns per view - need condition on landscape view or better on screen proportions (tablets, web) 
    body: GridView.count(
          crossAxisCount: 2,