# Blender PIP Qt add-on
Ultra Python module manager

![image](https://github.com/hannesdelbeke/pip-qt-addon/assets/3758308/3a80f178-d77d-4af6-8e63-26c258171ec4)

A Blender addon for managing Python modules inside Blender with PIP. (requires Qt to display the UI)




## Install

### Plugget install (recommended)
Search `pip-qt-addon` in [plugget-qt-addon](https://github.com/plugget/plugget-qt-addon), and click install  

Or run this code if you have the [plugget](https://github.com/plugget/plugget) Python package installed:
```python
import plugget
plugget.install("pip-qt-addon")
```

### Manual install
1. Install either by download .zip or downloading a release:  
See Blender's official docs on [installing add-ons](https://docs.blender.org/manual/en/latest/editors/preferences/addons.html#installing-add-ons).
2. install the [pip-qt](https://github.com/hannesdelbeke/pip-qt) dependency, and setup your qt environment in Blender. (see [bqt](https://github.com/techartorg/bqt))
3. Open the Blender preferences window  
4. Activate the addon tab for `Development: Python Module Manager`



## Use
Open from the menu `Window/Pip manager`



### Dependencies
developped on Windows, Mac support in progress
- UI [pip-qt](https://github.com/hannesdelbeke/pip-qt)
- pip wrapper [py-pip](https://github.com/hannesdelbeke/py-pip)


## other
- A similar, more basic pip-installer for Blender (without Qt): https://github.com/hannesdelbeke/blender_pip
