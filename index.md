# StoryModule Documentation

  To make this work, please require the module in a <b>Server Script</b>
  
  `local Module = require(game.ReplicatedStorage:WaitForChild('StoryModule'))`
  
## Messages
`Module.MakeDialog(String)`

`Module.NPCDialog(ImageURL,String,Instance.Character)`
## Dialog
Close Text Dialog
`Module.HideDialog()`
Create a countdown
`Module.Coutdown(Time,Callback)`
## Characters
Teleport all Players to a part.
`Module.teleport(Instance.Part)`
