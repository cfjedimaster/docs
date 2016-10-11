---

copyright:
  years: 2016

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# {{site.data.keyword.Bluemix_notm}} Dedicated でのツールチェーンの使い方
{: #toolchains-using_dedicated}

最終更新日: 2016 年 9 月 13 日
{: .last-updated}

ツールチェーンを使用して、日常的な開発、デプロイメント、運用の作業の生産性を向上させることができます。ツールチェーンをセットアップした後、
ツール統合を追加、削除、構成して、ツールチェーンへのアクセスを管理することができます。
{: shortdesc}

## ツール統合の構成
{: #configuring_a_tool_integration_dedicated}

ツールチェーンの作成時にツール統合の構成を据え置いた場合は、**「構成」**ボタンがタイルに表示されます。ツールチェーンの作成時にツール統合を構成した場合は、その構成設定を更新できます。

1. ダッシュボードの**「DEVOPS」**タブで、ツールチェーンをクリックして「ツール統合 (Tool Integrations)」ページを開きます。または、アプリの「概要」ページの右上隅にある**「ツールチェーンの表示」**をクリックします。次に、**「ツール統合 (Tool Integrations)」**をクリックします。
1. ツール統合の初回構成を行う必要がある場合は、そのツール統合のタイルで**「構成」**をクリックします。

  ![「構成」ボタン](images/toolchain_tile_configure.png)

 ツール統合の構成を完了したら、**「統合の保存 (Save Integration)」**をクリックします。
 
1. ツール統合の構成を更新する必要がある場合は、そのツール統合のタイルで、構成オプションにアクセスするためのメニューをクリックします。

  ![構成メニュー](images/toolchain_tile_menu.png)
 
 設定の更新を完了したら、**「統合の保存 (Save Integration)」**をクリックします。

## ツール統合の追加
{: #adding_a_tool_integration_dedicated}

ツールチェーンにツール統合を追加して構成することができます。

1. ダッシュボードの**「DEVOPS」**タブで、ツールチェーンをクリックして「ツール統合 (Tool Integrations)」ページを開きます。または、アプリの「概要」ページの右上隅にある**「ツールチェーンの表示」**をクリックします。次に、**「ツール統合 (Tool Integrations)」**をクリックします。
1. 追加するツール統合のリストを表示するために、追加ボタン (+) をクリックします。
1. 追加するツール統合をクリックします。
1. ツール統合を構成するために必要な情報を入力します。 
1. **「統合の作成 (Create Integration)」**をクリックして、ツールチェーンにツール統合を追加します。

## ツール統合の削除
{: #deleting_a_tool_integration}

ツールチェーンからツール統合を削除した場合、その削除を元に戻すことはできません。 

1. ダッシュボードの**「DEVOPS」**タブで、ツールチェーンをクリックして「ツール統合 (Tool Integrations)」ページを開きます。または、アプリの「概要」ページの右上隅にある**「ツールチェーンの表示」**をクリックします。次に、**「ツール統合 (Tool Integrations)」**をクリックします。
1. 削除するツール統合のタイルで、構成オプションにアクセスするためのメニューをクリックします。
1. ツールチェーンからツール統合を削除するために、**「削除」**をクリックします。
1. **「削除」**をクリックして確認します。 

## アクセスの管理
{: #managing_access_dedicated}

ユーザーにツールチェーンへのアクセス権を付与するには、ツールチェーンが関連付けられている組織にユーザーを追加します。それぞれのツールチェーンは特定の組織に関連付けられており、その組織のメンバーであるユーザーはだれでも、関連付けられたツールチェーンにアクセスできます。現在作業中の組織を表示するには、メニュー・バーの **{{site.data.keyword.avatar}}** アイコン ![Avatar アイコン](../icons/i-avatar-icon.svg)をクリックします。別のツールチェーン・セットにアクセスするには、別の組織に切り替えます。

{{site.data.keyword.Bluemix}} の組織やスペースにユーザーを追加すると、そのユーザーは、自分用の {{site.data.keyword.Bluemix_notm}} ID とパスワードで GitHub Enterprise にログインできるようになります。ユーザーがログインすると、そのユーザーのアカウントが作成されます。{{site.data.keyword.Bluemix_notm}} の組織やスペースにユーザーを追加しても、そのユーザーは、GitHub Enterprise リポジトリーに自動的に追加されるわけではありません。リポジトリーの管理特権を持った人がそのユーザーを追加する必要があります。詳しくは、[Dedicated GitHub Enterprise の使い方 (リンク先が新しいウィンドウで開きます)](../services/ghededicated/index.html){: new_window} を参照してください。

ユーザーを追加するには、以下の手順を実行します。 

1. ダッシュボードの**「DEVOPS」**タブで、ツールチェーンをクリックして「ツール統合 (Tool Integrations)」ページを開きます。**「管理」**をクリックします。または、アプリの「概要」ページの右上隅にある**「ツールチェーンの表示」**をクリックします。**「管理」**をクリックします。  
1. 組織へのリンクをクリックします。 
1. 「組織の管理」ページで、**「ユーザーの招待」**をクリックしてユーザーの E メール・アドレスを入力します。
1. {{site.data.keyword.Bluemix_notm}} の組織のユーザーを管理するための拡張権限を与える場合は、**「管理者」**、**「請求管理者」**、**「監査員」**のチェック・ボックスを 1 つ以上選択します。
1. **「招待 (INVITE)」**をクリックします。
1. **「保存」**をクリックします。

## ツールチェーンの削除
{: #deleting_a_toolchain_dedicated}

ツールチェーンを削除し、関連付けられたツール統合のうちどれを削除するかを指定できます。ツールチェーンを削除した場合、その削除を元に戻すことはできません。

1. ダッシュボードの**「DEVOPS」**タブで、ツールチェーンをクリックして「ツール統合 (Tool Integrations)」ページを開きます。**「管理」**をクリックします。または、アプリの「概要」ページの右上隅にある**「ツールチェーンの表示」**をクリックします。**「管理」**をクリックします。
1. **「ツールチェーンの削除 (Delete Toolchain)」**をクリックし、削除するツール統合を確認したり調整したりします。
1. ツールチェーンの名前を入力し、**「削除」**をクリックして削除を確認します。

 **ヒント**: GitHub Enterprise ツール統合を削除しても、関連する GitHub Enterprise リポジトリーは GitHub Enterprise から削除されません。リポジトリーは手動で GitHub Enterprise から削除する必要があります。