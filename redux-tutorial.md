<h1> Redux steps</h1>

*  create the initial state constant for the slice

* create the slice with the needed functions const nameSlice = createSlice()
* export the actions const nameActions = nameSlice.actions
* configure the store const store = configureStore(reducer: {})
* dispatch actions using const dispath = useDispatch()
* dispatch an action =>  dispatch(authActions.logout());
* get piece of state with useSelector()
ex. const isAuth = useSelector(state => state.auth.isAuthenticated);