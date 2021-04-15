
1. `npm i redux@4.0`

4 steps to create redux applicaiton:
1. Design the store
2. Define the actions
3. Create Reducer (Reducers are pure funcitons that is used to update store properties)
4. Set up the store

Create Reducer: 

```
let id = 0;
function reducer(state, action) {
    if (action.type === 'bugAdded') {
        return [
            ...state,
            {
                id: ++lastId,
                description: action.apyload.description,
                resolved: false
            }
        ]
    }

}```