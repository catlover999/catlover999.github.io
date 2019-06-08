#baseurl = "https://julienacker.dev/"
title = "Julien Acker"
theme = "pulp"
canonifyurls = true
hasCJKLanguage = true
# pygmentsCodefences = true
# pygmentsUseClasses = true
# googleAnalytics = "UA-141651935-1"

[taxonomies]
  series = "series"

[params]
    author = "Julien Acker"
    avatar = "avatar.jpg"
    favicon = "favicon.ico"
    description = """
        Just a person interested in tech.
    """
    publicationYear = "2019"
    # listPageDateFormat = "January, 2006" # See https://gohugo.io/functions/format/
    # singlePageDateFormat = "January 2, 2006"
    # custom_css = ["/css/custom.css"]
    # custom_js = ["/js/custom.js"]

[outputs]
    section = ["JSON", "HTML"]

[[menu.main]]
    identifier = "github"
    # name = "GitHub"
    pre = "<i class='fab fa-github fa-lg'></i>"
    url = "https://github.com/catlover999"
    weight = 30

[[menu.main]]
    identifier = "email"
    # name = "Email"
    pre = "<i class='fa fa-envelope fa-lg'></i>"
    url = "mailto:support@julienacker.dev"
    weight = 40
