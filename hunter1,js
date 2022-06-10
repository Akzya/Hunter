class commons{
getRoot = null
getReactRoot = null
getChatState = null 
searchObject = null
}


class game{
getTankPhysics = null
getTank = null  
getWorld = null  
getMines = null
getFlags = null
getPlayers = null
getMapBoundary = null    
getBattleState = null
getSupplies = null
getHealth = null
getStriker = null
getCamera = null
}


class hacks{
shaftHacks = null
acceleratiion = null
crusaderAngle = null
}


class vars{
repair = null
DD = null

  
}



commons.searchObject = function(object,item){
try {
for(let i=0; i<object.length;i++){
if(object[i].hasOwnProperty(item))
return object[i]

}      
} catch (error) {
    
}  
}
commons.getRoot = function(){
root = document.querySelector("#root")  
return root
}

commons.getReactRoot = function(){
return root._reactRootContainer._internalRoot.current.memoizedState.element.type.prototype.store.subscribers.array_hd7ov6$_0  
  
}


game.getTank = function(){
return commons.searchObject(commons.getReactRoot(),"tank").tank

  
  
  
}

game.getWorld = function(){
return game.getTank().world  
  
}

game.getMines = function(){
return game.getWorld().entities_0.array_hd7ov6$_0.at(0).components_0.array.at(15);  
  
  
  
}

game.getMapBoundary = function(){
return game.getWorld().entities_0.array_hd7ov6$_0.at(0).components_0.array.at(0).bounds
}


game.getPlayers = function(){
return game.getWorld().physicsScene_0.bodies_0.array_hd7ov6$_0  
  
  
  
}
game.getBattleState = function(){
  
return commons.getReactRoot().at(1).state.inBattle
}

game.getChatState = function(){
return document.querySelector(".sc-bwzfXH iokmvL")
}

game.getStriker = function(){
for(let i=0; i>game.getTank().components_0.array.length;i++){
if(game.getTank().components_0.array[i].hasOwnProperty("strikerWeapon_jjsiik$_0")){
return game.getTank().components_0.array[i]
 
  
}     
}  
}


game.getHealth = function(){
return game.getTank().components_0.array[1].isFullHealth()
  
  
}

game.getTankPhysics = function(){
return game.getTank().components_0.array[5].tankPhysicsComponent_tczrao$_0
  
  
  
}

game.getCamera = function(){
for (let i = 0; i < game.getTank().components_0.array.length; i++)
  {
    if(game.getTank().components_0.array[i].hasOwnProperty("followCamera_w8ai3w$_0"))
    return game.getTank().components_0.array[i].followCamera_0.currState_0
    
  }
}




hacks.shaftHacks = function()
{

 try {
   globalArray[corrArray].tank.components_0.array[100].maxElevationAngle_0 = 0.5
 } catch (error) {

 }

//

 try {
   globalArray[corrArray].tank.components_0.array[100].minElevationAngle_0 = -0.5
 } catch (error) {

 }
}

let pressCount = 0
document.addEventListener('keydown', function (event) { if (event.key === 'Home'){
pressCount ++
if(pressCount%2==1){
window.rz = setInterval(shaftHacks,1)


}

if(pressCount%2==0){

clearInterval(window.rz)

}



}})

hacks.acceleration = function()
    {
 try {
   globalArray[corrArray].tank.components_0.array[57].speedCharacteristics_0.acceleration = 2250
 } catch (error) {

 }}
let xpressCount = 0
document.addEventListener('keydown', function (event) { if (event.key === 'F9'){
xpressCount ++
if(xpressCount%2==1){
window.rx = setInterval(acceleration,1)


}

if(xpressCount%2==0){

clearInterval(window.rx)

}



}})

let epressCount = 0

hacks.crusaderAngle = function()
{

 try {
   globalArray[corrArray].tank.components_0.array[57].params_0.tiltStabilityMaxAngle = 1
 } catch (error) {

 }}
document.addEventListener('keydown', function (event) { if (event.key === 'Insert'){
epressCount ++
if(epressCount%2==1){
window.p = setInterval(crusaderAngle,1)


}

if(epressCount%2==0){

clearInterval(window.p)

}







}})
