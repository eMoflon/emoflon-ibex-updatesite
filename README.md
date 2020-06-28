# eMoflon::IBeX - Eclipse Plugin Update Site

## How to install
1. Install [GraphViz](http://www.graphviz.org/download/).
2. Get the latest version of the [Eclipse Modeling Tools](https://www.eclipse.org/downloads/packages/).
3. Install eMoflon::IBeX from this update site:
	https://emoflon.org/emoflon-ibex-updatesite/snapshot/updatesite/
    - Select the eMoflon::IBeX (Democles) feature to install eMoflon::IBeX along with the Democles pattern matching tool.
    - Select the eMoflon::IBeX (HiPE) feature to install eMoflon::IBeX along with the HiPE, our new parallel pattern matching tool.
    - Select the eMoflon::IBeX (Viatra) feature to install eMoflon::IBeX along with the [Viatra](https://www.eclipse.org/viatra/) pattern matching tool.
4. If dependencies were not found, go to Eclipse->Help->Install New Software...->Manage... and activate the following update sites:
    - Xtext: http://download.eclipse.org/modeling/tmf/xtext/updates/composite/releases/
    - PlantUML: http://hallvard.github.io/plantuml/
    - HiPE: https://hipe-devops.github.io/HiPE-Updatesite/hipe.updatesite/
    - Viatra: http://download.eclipse.org/viatra/updates/release/latest
5. Retry step 3.
    
Now you are ready to use eMoflon::IBeX.

6. (Optional) Install [GLPK for Windows](https://sourceforge.net/projects/winglpk/)
	or install GLPK via your package manager (Linux).
7. (Optional) Install [Gurobi](http://www.gurobi.com/downloads/gurobi-optimizer) 7.0.2
	(make sure it is exactly this version!)
8. (Optional) Install [Google OR](https://developers.google.com/optimization/introduction/installing/binary) (not necessary on 64-bit Windows)

Note that Gurobi is only free for academical use (but not for commercial).
