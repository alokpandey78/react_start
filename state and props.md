### state 
= can be change 

to use state object first of all intialize it and
define constructor function to owner of the inheritance of the component

  class Clock extends React.Component {
    constructor(props) {
      super(props);
      this.state = {date: new Date()};
    }

    render() {
      return (
        <div>
          <h1>Hello, world!</h1>
          <h2>It is {this.state.date.toLocaleTimeString()}.</h2>
        </div>
      );
    }
  }

### OR with class property

  class Clock extends React.Component {
      
      this.state = {counter: 0};

      handlerClick =() => {
          this.setState({
              counter: this.state.counter + 1;
          })
      }
      render() {
          return (
          <button onClick = {this.handlerClick}>
          {this.state.counter}
          </button>
          );
      }
  }


### props 
= fixed value, can not change


