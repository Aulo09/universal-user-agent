
app.LoadPlugin("DroidScriptUIKit")

function OnStart() {
   
    app.InitializeUIKit("#673ab7", "Light")
   
    lay = MUI.CreateLayout("Linear", "FillXY")
       
        edt = MUI.CreateTextEditOutline(0.85, "Left", "Type text", true)       
        lay.AddChild(edt)
   
    app.AddLayout(lay)
}
