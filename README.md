Trying to add tileset2.png to the overworld tilemap.


The steps i did:
1) Create new tilemap (check embed into map)
2) Place some tiles of the new tileset on overworld map to test
3) add code to base.js
   
//   const tileset2 = this.map.addTilesetImage("tileset2", "TilesetImage2", 32, 32, 1, 2);
   
4) add code to scene overworld
   
//    this.load.image("TilesetImage2", "./assets/prod/tilesets_and_maps/tileset2_extruded.png");

5) add code to index.min
   
 //    const j=this.map.addTilesetImage2("tileset2","TilesetImage2",32,32,1,2)

6) Starting game = only tileset 1 shows, tileset2 not :(


Tileset.png was already implemented before and works.

My error is when i load the game i have the tileset2 things balcked-out (no error message in console). 
the tiles of tileset.png work normaly.

Please advise me what im doing wrong in this code 🙏
