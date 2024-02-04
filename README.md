# To-Dolist

The Mean function of TODO list that after reloading the website content will  not go anywhere 
js code function saveData(){
    localStorage.setItem("data",listcontainer.innerHTML)
}
function showTask(){
    listcontainer.innerHTML = localStorage.getItem("data");
}
showTask();
