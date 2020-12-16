# django forms

- An HTML Form is a group of one or more fields/widgets on a web page, which can be used to collect information from users for submission to a server.

- The form attributes define the HTTP method used to send the data and the destination of the data on the server (action)

- action: The resource/URL where data is to be sent for processing when the form is submitted. I

- method: The HTTP method used to send the data: post or get.
- The GET method should only be used for forms that don't change user data (e.g. a search form).

- Declaring a Form
`from django import forms`
`class RenewBookForm(forms.Form):`
    `renewal_date = forms.DateField(help_text="Enter a date between now and 4 weeks (default 3).")`

- Form fields

- BooleanField, CharField, ChoiceField, TypedChoiceField, DateField, DateTimeField, DecimalField, DurationField, EmailField, FileField, FilePathField, FloatField, ImageField, IntegerField, GenericIPAddressField, MultipleChoiceField, TypedMultipleChoiceField, NullBooleanField, RegexField, SlugField, TimeField, URLField, UUIDField, ComboField, MultiValueField, SplitDateTimeField, ModelMultipleChoiceField, ModelChoiceField