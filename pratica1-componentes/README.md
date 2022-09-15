# 📚 Exercício 1

### I.  Create two new Components (manually or with CLI): WarningAlert and SuccessAlert.
<p>For this step I used the CLI to generate the components.</p>

`ng g c WarningAlert`
<br>
`ng g c SuccessAlert`


### II. Output them beneath each other in the AppComponent.
<p>Inside "app.component.html" I added the component tags.</p>

`<app-warning-alert></app-warning-alert>`
<br>
`<app-sucess-alert></app-sucess-alert>`

### III. Output a warning or success message in the Components.
<p>Inside the ".component.html" of each component I added the text of the respective components.</p>

`<p>This is a Warning, you are in danger!</p>`
<br>
`<p>This is a Success Alert, you are safe!</p>`


### IV. Style the Components appropriately (maybe some red/ green text?).
<p>Within the ".css" file of each component I styled it as needed.</p>

`p{`
<br>
`padding: 20px;`
<br>
`background-color: color_here;`
<br>
`border: 1px solid color_here;`
<br>
`color: color_here;`
<br>
`}`
