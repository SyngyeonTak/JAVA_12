# JAVA_12
## FRAME

1. Mouse Listener

* Mouse events notify when the user uses the mouse (or similar input device) to interact with a component. Mouse events occur when the cursor enters or exits a component's onscreen area and when the user presses or releases one of the mouse buttons.

* mouseReleased(MouseEvent):	Called just after the user releases a mouse button after a mouse press over the listened-to component.
citation: https://docs.oracle.com/javase/tutorial/uiswing/events/mouselistener.html

2. Window Listener

* The listener interface for receiving window events. The class that is interested in processing a window event either implements this interface (and all the methods it contains) or extends the abstract WindowAdapter class (overriding only the methods of interest). The listener object created from that class is then registered with a Window using the window's addWindowListener method. When the window's status changes by virtue of being opened, closed, activated or deactivated, iconified or deiconified, the relevant method in the listener object is invoked, and the WindowEvent is passed to it.<br>
citation: https://docs.oracle.com/javase/7/docs/api/java/awt/event/WindowListener.html

* windowClosing(WindowEvent)	Called in response to a user request for the listened-to window to be closed. To actually close the window, the listener should invoke the window's dispose or setVisible(false) method.<br>
citation:https://docs.oracle.com/javase/tutorial/uiswing/events/windowlistener.html
