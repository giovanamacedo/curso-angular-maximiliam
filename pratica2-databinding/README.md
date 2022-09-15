# 📚 Exercício 2

### 1. Add a Input field which updates a property ('username') via Two-Way-Binding

For this step, inside "app.component.html" I wrote:

`<label>Username</label>`
`<input type="text" class="form-control">`

In "app.component.ts" I created the username property:
`username = '';`

To do the two-way-binding I added in the input line of code:
`<input type="text" class="form-control" [(ngModel)]="username">`

At this stage it is important to make sure that you have imported the FormsModule.

### 2. Output the username property via String Interpolation (in a paragraph below the input)

For this step, below the created lines I added:
<p> {{ username }} </p>

### 3. Add a button which may only be clicked if the username is NOT an empty string
To add the button:
`<button class="btn btn-primary"> Reset user </button>`

To implement the condition, I added the button code line:
`<button class="btn btn-primary"  *[disabled]*="username === '' "> Reset user </button>`

### 4. Upon clicking the button, the username should be reset to an empty string

We can use the onclick events here, adding in the button's code line:
`<button class="btn btn-primary" [disabled]="username === '' " (click)="username = '' " > Reset user </button>`