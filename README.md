# Prims-algo
 it consist  a code  for prims algorithm  to the determine MST
 JAVA SOLUTION// PRIMS ALGORITHM
 THE CODE IS SO SIMPLE AND EASILY UNDERSTANABLE

 first i was confused with adjacency matrix how elements are being represented so : if you find difficulty in so here you can understand  :
adj.get(0) = [{1, 2}, {3, 6}]

Vertex 0 se vertex 1 tak edge hai, weight 2.
Vertex 0 se vertex 3 tak edge hai, weight 6. 
as it consist the array of two size 
[0]=weight
[1]=edge.
  Now how it work  so i Apply PRIM'S ALGORITHM:                            so ek priority queue rakhi jo elemnts ko store kr rhi hai on the basis of the  their least weight jiska wight sbse kam hoga vo front pr hoga ,
 so next liya hai ek MST array jo ye information rkhta hai ke kon kon sa node mst ka part ho chuka hai 
ek parent array bhi rkha jo hr node ka parent btata hai ek kabhi question may mst bnane ke liye  pucha jaye toh kaam aa jaye vaise koi kaamm nhi hai 
so   initially queue may (0,0,-1) 0 add kiya hai jiska weght 0 hai or parent -1  hai so ab hum q se niklenge element 
phir agar vo phle se he part hai mst ka toh ignore krenge agar nhi hai toh dekhenge os node se kha kha edge ja rhi hai  vo vertices nikla lo oska  weight agar vo vertices part nhi hai mst ka toh q may  osko add krao or repeat krty jao jb tk queue empty na ho jaye                                                                         

  I HOPE YOU UNDERSTAND IT WELL  :)     
