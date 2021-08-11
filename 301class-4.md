## **Forms**

**1- What is a ‘Controlled Component’?**

A Controlled Component is one that takes its current value through props and notifies changes through callbacks like onChange .

**2- Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.**

their responses should be saved each time a change has been comitted.
this prevents loss of form data and can make the page more responsive .

**3- How do we target what the user is entering if we have an event handler on an input field?**

with the onChange={this.handleChange} inside of the component's form element.

## **The Conditional (Ternary) Operator Explained**

**1-Why would we use a ternary operator?**

ternary operator are mush simplier . 
**2-Rewrite the following statement using a ternary statement:**

                    if(x===y){
                    console.log(true);
                    } else {
                    console.log(false);
                    }

` if(x===y)?console.log(true):console.log(false)


[React Docs - Forms](https://reactjs.org/docs/forms.html)

[The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)



