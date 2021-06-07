# *React* 
has four built-in methods that gets called, in this order, when mounting a component:

* constructor()
* getDerivedStateFromProps()
* render()
* componentDidMount()

*The render()* method is required and will always be called, the others are optional and will be called if you define them.


*componentDidMount*
The componentDidMount() method is called after the component is rendered.

This is where you run statements that requires that the component is already placed in the DOM.