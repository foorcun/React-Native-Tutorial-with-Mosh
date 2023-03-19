# The problem
![](https://github.com/foorcun/React-Native-Tutorial-with-Mosh/blob/master/images/safe%20area%20problem.PNG)


# the solution
## add to the import
```.sh
import { StyleSheet, Text, View , SafeAreaView} from 'react-native';
```

## change View into :

```.sh
    <SafeAreaView style={styles.container}>
      <Text>Hello exp...</Text>
      <StatusBar style="auto" />
    </SafeAreaView>
```
