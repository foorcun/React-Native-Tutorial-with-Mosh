[docs for view](https://reactnative.dev/docs/view)

\<View\> components is like a div in html.


# Bundling component and style

StyleSheet class kullanmak tavsiye ediliyor. Cunku typo larda validation aradigi icin ortaya cikartiyor.

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

# one liner (without bundling)
## version 1
```.sh
    <View flex={1} backgroundColor={'#fff'} alignItems={'center'} justifyContent={'center'} >
```
## version 2
```.sh
    <View flex= {1} backgroundColor='#fff' alignItems='center' justifyContent='center' >
```
## version 3 (parameters as javascript object)
```.sh
    <View style={{ backgroundColor: "#fff" }}>
```

## version 4
```.sh
    <View style={ containerStyle }>
```
```.sh
const containerStyle = {backgroundColor : '#fff'}
```
