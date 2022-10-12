# eMoflon::IBeX - Eclipse Plugin Update Site

## How to install
1. Install [GraphViz](http://www.graphviz.org/download/).
1. Get the latest version of the [Eclipse Modeling Tools](https://www.eclipse.org/downloads/packages/). You need at least Eclipse 2022-09.
1. Install eMoflon::IBeX from this update site:
	https://emoflon.org/emoflon-ibex-updatesite/snapshot/updatesite/
    - Select the eMoflon::IBeX (Democles) feature to install eMoflon::IBeX along with the Democles pattern matching tool.
    - Select the eMoflon::IBeX (HiPE) feature to install eMoflon::IBeX along with the HiPE, our new parallel pattern matching tool.
1. If dependencies were not found, go to Eclipse->Help->Install New Software...->Manage... and activate the following update sites:
    - Xtext: http://download.eclipse.org/modeling/tmf/xtext/updates/composite/releases/
    - PlantUML: http://hallvard.github.io/plantuml/
    - HiPE: https://hipe-devops.github.io/HiPE-Updatesite/hipe.updatesite/
1. Retry step 3.
    
Now you are ready to use eMoflon::IBeX.

1. (Optional) Install [GLPK for Windows](https://sourceforge.net/projects/winglpk/)
	or install GLPK via your package manager (Linux).
1. (Optional) Install [Gurobi](http://www.gurobi.com/downloads/gurobi-optimizer) 7.0.2
	(make sure it is exactly this version!)
1. (Optional) Install [Google OR](https://developers.google.com/optimization/introduction/installing/binary) (not necessary on 64-bit Windows)

Note that Gurobi is only free for academical use (but not for commercial).
