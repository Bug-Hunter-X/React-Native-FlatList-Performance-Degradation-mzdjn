# React Native FlatList Performance Issue

This repository demonstrates a common performance problem in React Native's FlatList component when dealing with large datasets and complex item rendering. The bug causes slow scrolling and janky animations, negatively impacting the user experience.

The `FlatListBug.js` file showcases the problematic implementation. The `FlatListBugSolution.js` file provides a solution using techniques like `ItemSeparatorComponent`, `keyExtractor`, `initialNumToRender`, `windowSize`, and optimizing item rendering to improve performance.