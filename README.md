# jquery.alert
Jquery Alert without Boostrap

## Example
![Example](https://en.shurimages.com/u/hT54dkL8pL.png)

## Usage

>		$('#trigger').click(function(){
			$.createAlert({
				attachAfter: '#trigger',
				title: 'You have reached the limit or your quota!',
				confirmText: 'Accept',
				confirmStyle: 'blue',
				callback: null
			});
			$.showAlert();
		});
		
> **#trigger** will be the element that will show the alert when clicked.


## Params

> **attachAfter** element after which the dialog html structure will be placed.

> **title** string to be shown as dialog title.

> **confirmText** string to the "accept" button.

> **confirmStyle** style to the "accept" button. It's the name of a css class. You can add more styles in the alert.css.

> **callback** function (without params) that will be executed by clicking the "accept" button. It is optional but you can also leave it null.
