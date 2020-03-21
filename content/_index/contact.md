+++
fragment = "contact"
#disabled = true
date = "2017-09-10"
weight = 1100
#background = "light"
form_name = "defaultContact"

title = "Contactez-nous"
subtitle  = "Nous sommes à votre écoute ([nos coordonnées sont aussi disponibles ici](/member))"

post_url = "https://formspree.io/mlenlwrw" #default: formspree.io
email = "bjalon@qastia.com"
button = "Envoyer" # defaults to theme default
#netlify = false

# Optional google captcha
#[recaptcha]
#  sitekey = ""

[message]
  success = "Merci pour votre aide et commentaires" # defaults to theme default
    error = "Une erreur s'est produite" # defaults to theme default

# Only defined fields are shown in contact form
[fields.name]
  text = "Votre nom *"
  error = "Entrez votre nom et prénom" # defaults to theme default

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
  value = "www.preuillysurclaise.fr"

[[fields.hidden]]
  name = "_next"
  value = "http://www.preuillysurclaise.fr/merci"
+++
