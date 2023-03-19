\<View\> components is like a div in html.


# Bundling component and style

```.sh
<View style={styles.container}>
```
```.sh
const styles = StyleSheet.create({
  container: {
    flex: 1,
    backgroundColor: '#fff',
    alignItems: 'center', // horizontal center
    justifyContent: 'center', // vertiacal center
  },
});
```
