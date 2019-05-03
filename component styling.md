
### Add class in react component
    className = "info" 

### Add style in component
    style = {{display:'inline-block',marginLeft:10}}

### get github user details
https://api.github.com/users/vikashraj144

### Read Form data from input
    ref is used for to get data submitted from form
    <input type="text"
    ref = {(input)=> this.userName=input}
    placeholder ="name" required />


### Through state
    state = {userName:''};
    render(){
    <input type="text"
    value={this.state.userName}
    onChange={(event)=>this.setState({userName:event.target.value})}
    placeholder ="name" required />
    }


### use axios 
    https://www.npmjs.com/package/axios