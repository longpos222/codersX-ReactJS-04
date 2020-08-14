# codersX-ReactJS-04

```javascript
  <script type="text/babel">

      const todos = [
        'Go to market.',
        'Buy food.',
        'Make dinner.'
      ];

      const ThingsTodo = todos.map(
        function(thing){
          return <li> {thing} </li>;
        }
      );

      const App = <ul> {ThingsTodo} </ul>;
      const root = document.getElementById('root');
      ReactDOM.render(App, root);

  </script>
```