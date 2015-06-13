# Connectome

This web-based tool allows to visualize the Connectome data that describes how the regions of the brain are interconnected.
Particularly, the tools enable to perform the exploration of the intrinsic geometry of the brain, by letting the user
 switch quickly different topological spaces where the connectome is embedded.
With a simple and easy-to-use interface, users can explore all the connections with a edge-on-demand technique and focus on
very specific area by switching on and off regions of the brain. Simple analytics such as nodal strength and shortest path
trees can be computed on the fly. This tool has been developed with virtual reality in mind and it is compatible with
Head Mounted Displays such as Oculus Rift (both DK1 and DK2).

#How to use it
The web-based tool is accessible [here](gioconte.github.com). It has been optimized for Google Chrome Browser.
Users can upload data and visualize them. All the files needed are in ".csv" format and specifically should be structured are as follows:
-locations files (4): each of them contains a different file locations. Each row of the file contains three values that represent the x,y,z coordinates. Each value is separated by a coma.
-network file: this file contains the adjacency matrix of the connectome network. Each value within the same row is separated by a coma. The tool is optimized to deal with weighted graph.
-labelkey file: each row contains the Freesurfer Id label to which the node belongs.

Before uploading the file, make sure to remove the last blank row of each file, otherwise data will not be displayed correctly.

#Acknoledgement

The tool was entirely developed by Giorgio Conte who belongs to the [Creative Coding Research Group](https://www.evl.uic.edu/creativecoding/), directed by Prof.
Angus Forbes. The research group is part of the [Electronic Visualization Lab](https://www.evl.uic.edu) (EVL) at University of Illinois at Chicago (UIC).
This research is being done in collaboration with Alex Leow, Olusola Ajilore, and Allen Ye, all belonging to UIC Department of Psychiatry.