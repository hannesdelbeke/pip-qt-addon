# Blender PIP Qt add-on
A Blender Add-on wrapper around [pip-qt](https://github.com/hannesdelbeke/pip-qt) to manage your Python modules in Blender.  
🔍Search, ⚙️(un)install, 📃list

![image](https://github.com/hannesdelbeke/pip-qt-addon/assets/3758308/3a80f178-d77d-4af6-8e63-26c258171ec4)





## Install

### Plugget install (recommended)
1. install the [plugget-qt-addon](https://github.com/plugget/plugget-qt-addon)
2. Search & install `pip-qt-addon` using the plugget qt addon  
or
1. Install the [plugget](https://github.com/plugget/plugget) Python package
2. And run the code below:
```python
import plugget
plugget.install("pip-qt-addon")
```

### Manual install
1. Install either by download .zip or downloading a release:  
See Blender's official docs on [installing add-ons](https://docs.blender.org/manual/en/latest/editors/preferences/addons.html#installing-add-ons).
2. Install the [pip-qt](https://github.com/hannesdelbeke/pip-qt) dependency
3. Setup your qt environment in Blender. (see [bqt](https://github.com/techartorg/bqt))
4. Open the Blender preferences window  
5. Activate the addon tab for `Development: Python Module Manager`


## Instructions
Open the window from the menu `Window/Pip manager`  
For instructions, see [pip-qt](https://github.com/hannesdelbeke/pip-qt) 



## other
- A similar, more basic pip-installer for Blender (without Qt): https://github.com/hannesdelbeke/blender_pip
