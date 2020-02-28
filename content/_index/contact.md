+++
fragment = "contact"
#disabled = true
date = "2017-09-10"
weight = 1100
#background = "light"
form_name = "defaultContact"

title = "Parlons-nous"
subtitle  = "Nous sommes à votre écoute. <br> <br> <small>Our English-speaking friends are welcome to communicate in English.</small>"

post_url = "https://formspree.io/mlenlwrw" #default: formspree.io
email = "bjalon@qastia.com"
button = "Envoyer" # defaults to theme default
#netlify = false

# Optional google captcha
#[recaptcha]
#  sitekey = ""

[message]
  success = "Merci pour votre aide et commentaire" # defaults to theme default
    error = "Une erreur s'est produite" # defaults to theme default

# Only defined fields are shown in contact form
[fields.name]
  text = "Votre nom *"
  error = "Entrez votre nom et prénom" # defaults to theme default

[fields.email]
  text = "Votre Email *"
  error = "Entrer votre adresse email" # defaults to theme default

[fields.phone]
  text = "Votre téléphone *"
  error = "Entrez votre téléphone" # defaults to theme default

[fields.message]
  text = "Votre message *"
  error = "Saisissez votre message" # defaults to theme default

# Optional hidden form fields
# Fields "page" and "site" will be autofilled
[[fields.hidden]]
  name = "page"

[[fields.hidden]]
  name = "someID"
  value = "unis.preuilly.com"

[[fields.hidden]]
  name = "_next"
  value = "http://www.preuilly.net/merci"
+++
