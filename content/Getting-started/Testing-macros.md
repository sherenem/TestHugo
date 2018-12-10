---
title: "Macros"
date: 2018-11-14T11:48:37+05:30
draft: false
weight: 2
toc : true
---

{{% toc %}} {{% /toc %}}

# Images

![agence](https://github.com/vjeantet/vjeantet.fr/raw/master/static/images/sgthon/C.jpg?height=200px)

# Notes, panels, expands

{{% alert info %}}**Info:** testing info style{{% /alert %}}
{{% alert success %}}**Tip:** testing{{% /alert %}}
{{% alert warning %}}**Note:** test{{% /alert %}}
{{% alert danger %}}**Warning:** test{{% /alert %}}

{{% panel theme="default" header="panel test" %}}this is a panel{{% /panel %}}

{{% notice tip %}}
This is another styling of tip
{{% /notice %}}

{{%expand "Expand block working ?" %}} Yes! YAY! {{% /expand%}}


{{% panel theme="default" header="panel test" %}}{{%expand "Expand block still working ?" %}} 
yes but not with text inside the panel. We can only have a panel heading.{{% /expand%}}{{% /panel %}}

# Excerpts

{{%panel theme="success" header="testing excerpt" %}}
{{%excerpt%}}THIS PART IS AN EXCERPT! To see the excerpt-include, see SSO page!{{% /excerpt%}}{{% /panel %}}

# Code blocks

{{< highlight go "linenos=table">}}
public class HardCodedSecretCallbackHandler extends AbstractSecretCallbackHandler {
     protected void handleSingleSecretCallback(SingleSecretCallback singleSecretCallback) {
            singleSecretCallback.setSecret("password");
     }
}
{{< / highlight >}}

Testing if `monospace`  works.

