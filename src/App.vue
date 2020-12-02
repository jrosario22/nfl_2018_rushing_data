<template>
  <div id="app">
    <Header />
    <Intro />
    <Outliers />
    <LinearRegression />
    <DecisionTree />
    <KNearest />
  </div>
</template>

<script>
import Header from "./components/Header";
import Intro from "./components/Intro";
import Outliers from "./components/Outliers";
import LinearRegression from "./components/LinearRegression";
import DecisionTree from "./components/DecisionTree";
import KNearest from "./components/K-Nearest";

export default {
  name: "App",
  components: {
    Header,
    Intro,
    Outliers,
    LinearRegression,
    DecisionTree,
    KNearest,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
