+++
title = "Manage your account"
description = ""
weight = 1
+++


## Sign Up
1.	Go to  <a href="https://research.cip.cgiar.org/agrofims/dev/0212" target="_blank">AgroFIMS</a>.
2.	Enter your email, password, name, last name, organization and country. 
3.	Click Create.
4.	Your account has been created. You can Log in and start using AgroFIMS. 
5.	An email will be sent to your mailbox to confirm your account. 
{{< alert style="warning" >}} Don’t forget to check your spam folder if you don’t see the email in your inbox! {{< /alert >}}

### Checking your Hugo installation
Run the following command in your terminal to check if Hugo is installed.
{{< code lang="bash" >}}
hugo version
{{< /code >}}
Make sure the version name mentions <i>extended</i>, to indicate you've installed the extended version of Hugo, which is required for this theme.

## Creating a site
Create a new site *docs* (you may choose any name you want). In your projects root folder, run the following command:
{{< code lang="bash" >}}
hugo new site docs
{{< /code >}}
This will create a new folder <code>/docs</code> with all required files in it.

### Installing the theme
Download and copy the theme files into <code>/docs/themes/ace-documentation</code> or use <i>git</i> to clone the repository to that directory:
{{< code lang="bash" >}}
cd docs
cd themes
git clone https://github.com/vantagedesign/ace-documentation
{{< /code >}}

After theme installation, the <code>/docs/themes/ace-documentation</code> folder should contain the file <code>theme.toml</code>, along with all other theme files.

### Configuring your hugo site to use the theme
Inside your site's folder, <code>/docs</code>, you will find a file called <code>config.toml</code>. This is the configuration file for your site. Open it and configure it to use the Ace theme by setting the following value:
{{< code lang="toml" >}}
theme = "ace-documentation"
{{< /code >}}


## Installing example content
You can add some sample content to your site by placing the contents of the <code>exampleSite</code> directory in your <code>/docs</code> directory.
