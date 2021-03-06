.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the Button.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_Button:

Button
======

**Inherits:** :ref:`BaseButton<class_basebutton>` **<** :ref:`Control<class_control>` **<** :ref:`CanvasItem<class_canvasitem>` **<** :ref:`Node<class_node>` **<** :ref:`Object<class_object>`

**Inherited By:** :ref:`OptionButton<class_optionbutton>`, :ref:`ColorPickerButton<class_colorpickerbutton>`, :ref:`CheckButton<class_checkbutton>`, :ref:`MenuButton<class_menubutton>`, :ref:`ToolButton<class_toolbutton>`, :ref:`CheckBox<class_checkbox>`

**Category:** Core

Brief Description
-----------------

Standard themed Button.

Member Functions
----------------

+--------------------------------+----------------------------------------------------------------------------------------------------------+
| :ref:`Texture<class_texture>`  | :ref:`get_button_icon<class_Button_get_button_icon>`  **(** **)** const                                  |
+--------------------------------+----------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`        | :ref:`get_clip_text<class_Button_get_clip_text>`  **(** **)** const                                      |
+--------------------------------+----------------------------------------------------------------------------------------------------------+
| :ref:`String<class_string>`    | :ref:`get_text<class_Button_get_text>`  **(** **)** const                                                |
+--------------------------------+----------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`          | :ref:`get_text_align<class_Button_get_text_align>`  **(** **)** const                                    |
+--------------------------------+----------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`        | :ref:`is_flat<class_Button_is_flat>`  **(** **)** const                                                  |
+--------------------------------+----------------------------------------------------------------------------------------------------------+
| void                           | :ref:`set_button_icon<class_Button_set_button_icon>`  **(** :ref:`Texture<class_texture>` texture  **)** |
+--------------------------------+----------------------------------------------------------------------------------------------------------+
| void                           | :ref:`set_clip_text<class_Button_set_clip_text>`  **(** :ref:`bool<class_bool>` enabled  **)**           |
+--------------------------------+----------------------------------------------------------------------------------------------------------+
| void                           | :ref:`set_flat<class_Button_set_flat>`  **(** :ref:`bool<class_bool>` enabled  **)**                     |
+--------------------------------+----------------------------------------------------------------------------------------------------------+
| void                           | :ref:`set_text<class_Button_set_text>`  **(** :ref:`String<class_string>` text  **)**                    |
+--------------------------------+----------------------------------------------------------------------------------------------------------+
| void                           | :ref:`set_text_align<class_Button_set_text_align>`  **(** :ref:`int<class_int>` align  **)**             |
+--------------------------------+----------------------------------------------------------------------------------------------------------+

Member Variables
----------------

- :ref:`int<class_int>` **align** - Text alignment policy for the button's text, use one of the ALIGN_* constants.
- :ref:`bool<class_bool>` **clip_text** - When this property is enabled, text that is too large to fit the button is clipped, when disabled the Button will always be wide enough to hold the text. This property is disabled by default.
- :ref:`bool<class_bool>` **flat** - Flat buttons don't display decoration.
- :ref:`Texture<class_texture>` **icon** - Button's icon, if text is present the icon will be placed before the text.
- :ref:`String<class_string>` **text** - The button's text that will be displayed inside the button's area.

Numeric Constants
-----------------

- **ALIGN_LEFT** = **0** --- Align the text to the left.
- **ALIGN_CENTER** = **1** --- Align the text to the center.
- **ALIGN_RIGHT** = **2** --- Align the text to the right.

Description
-----------

Button is the standard themed button. It can contain text and an icon, and will display them according to the current :ref:`Theme<class_theme>`.

Member Function Description
---------------------------

.. _class_Button_get_button_icon:

- :ref:`Texture<class_texture>`  **get_button_icon**  **(** **)** const

.. _class_Button_get_clip_text:

- :ref:`bool<class_bool>`  **get_clip_text**  **(** **)** const

.. _class_Button_get_text:

- :ref:`String<class_string>`  **get_text**  **(** **)** const

.. _class_Button_get_text_align:

- :ref:`int<class_int>`  **get_text_align**  **(** **)** const

.. _class_Button_is_flat:

- :ref:`bool<class_bool>`  **is_flat**  **(** **)** const

.. _class_Button_set_button_icon:

- void  **set_button_icon**  **(** :ref:`Texture<class_texture>` texture  **)**

.. _class_Button_set_clip_text:

- void  **set_clip_text**  **(** :ref:`bool<class_bool>` enabled  **)**

.. _class_Button_set_flat:

- void  **set_flat**  **(** :ref:`bool<class_bool>` enabled  **)**

.. _class_Button_set_text:

- void  **set_text**  **(** :ref:`String<class_string>` text  **)**

.. _class_Button_set_text_align:

- void  **set_text_align**  **(** :ref:`int<class_int>` align  **)**


