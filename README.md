# HorizontalExtendedTile
Flutter HorizontalExtendedTile

This Includes HorizontalExtendedTile As we don't have any ExtendedTile to use horizontally.

To use change width in the end of code according to your content.

Container(
              margin: EdgeInsets.symmetric(vertical: 20.0),
              width: 200, // This need to change in code according to your content display 
              child: ListView(
                  scrollDirection: Axis.horizontal, children: widget.children)),
