3D digitizing tools
===================

.. _3d_digitizing:

.. tip:: use document **User manual - Point cloud**

Clipbox
--------

Clipbox tool is used to clip a selected part of the point cloud map. When the clipbox is set,
only the clipped part is visible, other parts of the point cloud map will be hidde.

Add new feature
---------------

When the add tool is active drawing new object is possible on the selected active
layer. By default the add tool can be activated with the button "e".

Edit existing feature
---------------------

When the edit tool is active, objects on the point cloud map are selectable.
Selected objects can be edited (add new points, remove, change parameters on
form, etc.). By default the edit tool can be activated with button "r".
Edited points can be moved on selected axis. (button "x")

Actions:
* Left click on object (single click): First click selects the object. (point, line,
polygon) Other objects cant be selected until the current object is deselected.
* When the object is selected:
* Position of the edited object's point can be changed along x, y, z axes.
* Add new point to the end of the object. (ctrl + click on line of the
object)
* Add new point on the line of the object. (between existing points) (shift
* click on the line of the object)
* Remove object points: Remove points of the selected object. (buttons
"delete" or "d")
* Active object edit can be deactivated with button "esc".

* Layer selection: Selected layer (active layer):
* When another layer is selected, active drawn object can be saved, removed,
or continued.
* Save parameters: Parameters can be saved through "open form" tool or when the
"space" button is pressed.
* Shortcuts: More information about shortcuts under section "Shortcuts".

Undo / redo
-----------

Undo or redo tool is active when add or edit tool is selected.
* Undo: Undo action.
* Redo: Redo action.

Delete feature
--------------

Delete tool is active when an object is selected in the point cloud map.
* Remove object: Remove selected object.

Copy / paste feature
--------------------

Join line features
------------------

Snapping
---------

Snap to vertex tool can be activated or deactivated. When drawing an object, and
the pointer is near to another object, it will jump or snap to the other object's
point. Snap to vertex can be used when an object is edited or a new is created.

* line
* vertex
* line + vertex

Open attribute form
-------------------

Form can be opened with open object's form tool. When the form is opened it is filled
with fields where the object's parameter can be changed. (by default form can be opened
with "space" button)

Actions on form:
* Data: Fields where the object parameters can be set or changed.
* Save: Save object's parameters.
* Cancel: Cancel and close object popup window.
* Remove: Remove selected object.
* Open point cloud: Open "Point cloud" section.

:ref:`Attribute form <attribute_form>`

Shortcuts
---------

:ref:`Shortcuts <shortcuts>`