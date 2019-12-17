# LoDb

    LoDb/Load default bind.
        is Python Binding that will allowed you to load Gui, Widget and etc.
        from PySide or PyQt.

    Most case this is for create user interface in DCC(Digital Content Creation).

    Then we can add function in our code and load it as a signal/method.

## Origin

    Nathan Horne
        http://nathanhorne.com/

    Perry Leijten
        https://www.perryleijten.com/

## List of binding

    PyQt5
    PyQt4
    PySide2
    PySide 

## List of function

    - loadUiType
    ('workaround to be able to load QT designer uis with both PySide and PyQt)
    
    - wrapinstance
    (workaround to be able to wrap objects with both PySide and PyQt)

### How to use

    Import it as a module

    '''
    
    from LoDb import *
    from LoDb import loadUiType
    from LoDb import wrapinstance

    '''
