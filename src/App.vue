<template>
  <div id="app">
    <div class="header">
      <input type="text" class="inputTask" />
      <button class="addTask btn">Add</button>
    </div>
    <div class="main">
      <ul class="tasks">
        <li class="task">
          <input type="checkbox" class="checkbox"/>
          <input type="text" />
          <img src="../public/img/edit.png" height="25px" />
          <img src="../public/img/trash.png" alt="" height="25px">
        </li>
              </ul>
    </div>
    <div class="footer">
      <button class="btn">ALL</button>
      <button class="btn">Completer</button>
      <button class="btn">Not Completed</button>
    </div>
  </div>
</template>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Inter&display=swap");
* {
  font-family: "Inter", sans-serif;
}
.header {
  margin-top: 50px;
  margin-bottom: 56px;
  text-align: center;
}

.inputTask {
  margin-left: 40px;
  width: 400px;
  height: 50px;
  background-color: #d1c9c9;
  border: none;
  border-radius: 10px;
  padding-left: 20px;
  font-size: 16px;
  outline: none;
}

.btn {
  background: #a672ff;
  color: white;
  border-radius: 10px;
  border-color: white;
}

.addTask {
  width: 107px;
  height: 50px;
  margin-left: 35px;
  font-size: 16px;
}

.tasks {
  display: flex;
  flex-direction: column;
  align-items: center;
  display: flex;
  justify-content: center;
}

.task {
  background-color: #d1c9c9;
  border-radius: 10px;
  height: 60px;
  width: 621px;
  list-style-type: none;
  margin: 7px;
  display: flex;
    align-items: center;
}

.checkbox{
  border-radius: 100%;
  color: #a672ff;
}
</style>
