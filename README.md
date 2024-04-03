
```
CNlightnovel Crawler
├─ .editorconfig
├─ .gitattributes
├─ .github
│  ├─ FUNDING.yml
│  ├─ ISSUE_TEMPLATE
│  │  ├─ 1_general.md
│  │  ├─ 2_new-source.md
│  │  ├─ 3_source-issue.md
│  │  └─ 4_bug_report.md
│  ├─ contribs.json
│  ├─ dependabot.yml
│  └─ workflows
│     ├─ index-gen.yml
│     ├─ lint-pr.yml
│     └─ release.yml
├─ .gitignore
├─ Aptfile
├─ LICENSE
├─ Procfile
├─ README.pip
├─ app.json
├─ compose.yml
├─ etc
│  └─ wuxiaworld.com
│     ├─ help.md
│     ├─ wuxia.proto
│     └─ wuxia.proto.json
├─ lncrawl
│  ├─ VERSION
│  ├─ __init__.py
│  ├─ __main__.py
│  ├─ assets
│  │  ├─ __init__.py
│  │  ├─ banner.py
│  │  ├─ chars.py
│  │  ├─ colors.py
│  │  ├─ epub
│  │  │  ├─ __init__.py
│  │  │  ├─ chapter.xhtml
│  │  │  ├─ cover.xhtml
│  │  │  └─ style.css
│  │  ├─ languages.py
│  │  ├─ user_agents.py
│  │  ├─ version.py
│  │  └─ web
│  │     ├─ __init__.py
│  │     ├─ script.js
│  │     └─ style.css
│  ├─ binders
│  │  ├─ __init__.py
│  │  ├─ calibre.py
│  │  ├─ epub.py
│  │  ├─ text.py
│  │  └─ web.py
│  ├─ bots
│  │  ├─ __init__.py
│  │  ├─ _sample.py
│  │  ├─ console
│  │  │  ├─ __init__.py
│  │  │  ├─ get_crawler.py
│  │  │  ├─ integration.py
│  │  │  ├─ login_info.py
│  │  │  ├─ open_folder_prompt.py
│  │  │  ├─ output_style.py
│  │  │  ├─ range_selection.py
│  │  │  └─ resume_download.py
│  │  ├─ discord
│  │  │  ├─ __init__.py
│  │  │  ├─ config.py
│  │  │  ├─ discord_bot.py
│  │  │  └─ message_handler.py
│  │  ├─ lookup
│  │  │  ├─ __init__.py
│  │  │  ├─ analyze.py
│  │  │  ├─ generator.py
│  │  │  └─ prompts.py
│  │  └─ telegram
│  │     └─ __init__.py
│  ├─ constants.py
│  ├─ core
│  │  ├─ __init__.py
│  │  ├─ app.py
│  │  ├─ arguments.py
│  │  ├─ browser.py
│  │  ├─ cleaner.py
│  │  ├─ crawler.py
│  │  ├─ display.py
│  │  ├─ downloader.py
│  │  ├─ exeptions.py
│  │  ├─ logconfig.py
│  │  ├─ novel_info.py
│  │  ├─ novel_search.py
│  │  ├─ proxy.py
│  │  ├─ scraper.py
│  │  ├─ soup.py
│  │  ├─ sources.py
│  │  └─ taskman.py
│  ├─ models
│  │  ├─ __init__.py
│  │  ├─ chapter.py
│  │  ├─ formats.py
│  │  ├─ meta.py
│  │  ├─ novel.py
│  │  ├─ search_result.py
│  │  ├─ session.py
│  │  └─ volume.py
│  ├─ templates
│  │  ├─ __init__.py
│  │  ├─ browser
│  │  │  ├─ __init__.py
│  │  │  ├─ basic.py
│  │  │  ├─ chapter_only.py
│  │  │  ├─ general.py
│  │  │  ├─ login.py
│  │  │  ├─ optional_volume.py
│  │  │  ├─ searchable.py
│  │  │  └─ with_volume.py
│  │  ├─ madara.py
│  │  ├─ mangastream.py
│  │  ├─ novelfull.py
│  │  ├─ novelmtl.py
│  │  ├─ novelpub.py
│  │  ├─ novelupdates.py
│  │  └─ soup
│  │     ├─ __init__.py
│  │     ├─ chapter_only.py
│  │     ├─ general.py
│  │     ├─ optional_volume.py
│  │     ├─ searchable.py
│  │     └─ with_volume.py
│  ├─ utils
│  │  ├─ __init__.py
│  │  ├─ imgen.py
│  │  ├─ kindlegen_download.py
│  │  ├─ material_colors.py
│  │  ├─ pbincli.py
│  │  ├─ platforms.py
│  │  ├─ ratelimit.py
│  │  ├─ sockets.py
│  │  ├─ ssl_no_verify.py
│  │  ├─ tilings.py
│  │  └─ uploader
│  │     ├─ __init__.py
│  │     ├─ anonfiles.py
│  │     ├─ gofile.py
│  │     └─ google_drive.py
│  └─ webdriver
│     ├─ __init__.py
│     ├─ elements.py
│     ├─ job_queue.py
│     ├─ local.py
│     ├─ remote.py
│     └─ scripts.py
├─ requirements-app.txt
├─ requirements-bot.txt
├─ requirements-dev.txt
├─ requirements.txt
├─ res
│  ├─ lncrawl-icon.png
│  ├─ lncrawl-web.png
│  └─ lncrawl.ico
├─ scripts
│  ├─ Dockerfile
│  ├─ entry_point.sh
│  ├─ index_gen.py
│  ├─ lint.bat
│  ├─ lint.sh
│  ├─ lncrawl.service
│  ├─ publish.bat
│  ├─ publish.sh
│  ├─ push_tag.bat
│  ├─ push_tag.sh
│  ├─ push_tag_force.bat
│  ├─ push_tag_force.sh
│  ├─ rebrandly.sh
│  ├─ start.sh
│  └─ stop.sh
├─ setup.cfg
├─ setup.py
├─ setup_pyi.py
├─ sources
│  ├─ __init__.py
│  ├─ _examples
│  │  ├─ _00_basic.py
│  │  ├─ _01_general_soup.py
│  │  ├─ _02_searchable_soup.py
│  │  ├─ _03_chapter_only_soup.py
│  │  ├─ _04_searchable_chapter_only_soup.py
│  │  ├─ _05_with_volume_soup.py
│  │  ├─ _06_searchable_with_volume_soup.py
│  │  ├─ _07_optional_volume_soup.py
│  │  ├─ _08_searchable_optional_volume_soup.py
│  │  ├─ _09_basic_browser.py
│  │  ├─ _10_general_browser.py
│  │  ├─ _11_searchable_browser.py
│  │  ├─ _12_chapter_only_browser.py
│  │  ├─ _13_searchable_chapter_only_browser.py
│  │  ├─ _14_with_volume_browser.py
│  │  ├─ _15_searchable_with_volume_browser.py
│  │  ├─ _16_optional_volume_browser.py
│  │  └─ _17_searchable_optional_volume_browser.py
│  ├─ _index.json
│  ├─ _rejected.json
│  ├─ ar
│  │  ├─ arnovel.py
│  │  ├─ kolnovel.py
│  │  └─ rewayatclub.py
│  ├─ en
│  │  ├─ 1
│  │  │  └─ 1stkissnovel.py
│  │  ├─ 4
│  │  │  └─ 4scanlation.py
│  │  ├─ 8
│  │  │  ├─ 888novel.py
│  │  │  └─ 88tang.py
│  │  ├─ a
│  │  │  ├─ allnovel.py
│  │  │  ├─ allnovelfull.py
│  │  │  ├─ americanfaux.py
│  │  │  ├─ amnesiactl.py
│  │  │  ├─ ancientheartloss.py
│  │  │  ├─ anythingnovel.py
│  │  │  ├─ aquamanga.py
│  │  │  ├─ arangscans.py
│  │  │  ├─ asadatrans.py
│  │  │  ├─ asianhobbyist.py
│  │  │  ├─ asianovel.py
│  │  │  └─ automtl.py
│  │  ├─ b
│  │  │  ├─ babelnovel.py
│  │  │  ├─ bakapervert.py
│  │  │  ├─ bato.py
│  │  │  ├─ beautymanga.py
│  │  │  ├─ bestlightnovel.py
│  │  │  ├─ blackboxtl.py
│  │  │  ├─ bonnovel.py
│  │  │  ├─ booknet.py
│  │  │  ├─ boxnovel.py
│  │  │  ├─ boxnovelcom.py
│  │  │  ├─ boxnovelonline.py
│  │  │  ├─ boxnovelorg.py
│  │  │  └─ bronovel.py
│  │  ├─ c
│  │  │  ├─ centinni.py
│  │  │  ├─ chickengege.py
│  │  │  ├─ chrysanthemumgarden.py
│  │  │  ├─ clicknovel.py
│  │  │  ├─ coffeemanga.py
│  │  │  ├─ creativenovels.py
│  │  │  ├─ crescentmoon.py
│  │  │  └─ fu_kemao.py
│  │  ├─ d
│  │  │  ├─ daonovel.py
│  │  │  ├─ daotranslate.py
│  │  │  ├─ demontrans.py
│  │  │  ├─ divinedaolibrary.py
│  │  │  ├─ dmtrans.py
│  │  │  ├─ dobelyuwai.py
│  │  │  ├─ dragon_tea.py
│  │  │  ├─ dsrealmtrans.py
│  │  │  └─ dummynovels.py
│  │  ├─ e
│  │  │  ├─ engnovel.py
│  │  │  └─ exiledrebels.py
│  │  ├─ f
│  │  │  ├─ fanfiction.py
│  │  │  ├─ fanstrans.py
│  │  │  ├─ fantasyworldonline.py
│  │  │  ├─ faqwiki.py
│  │  │  ├─ fictionpress.py
│  │  │  ├─ flyinglines.py
│  │  │  ├─ foxteller.py
│  │  │  ├─ freefullnovel.py
│  │  │  ├─ freelightnovel.py
│  │  │  ├─ freemanga.py
│  │  │  ├─ freewebnovel.py
│  │  │  ├─ fringecapybara.py
│  │  │  ├─ fsapk.py
│  │  │  ├─ fujitrans.py
│  │  │  ├─ fullnovellive.py
│  │  │  └─ fuyuneko.py
│  │  ├─ g
│  │  │  └─ gravitytales.py
│  │  ├─ h
│  │  │  ├─ hanyunovels.py
│  │  │  ├─ harimanga.py
│  │  │  ├─ hostednovel.py
│  │  │  ├─ hotnovelfull.py
│  │  │  ├─ hs2ppe.py
│  │  │  └─ hui3r.py
│  │  ├─ i
│  │  │  ├─ imperfectcomic.py
│  │  │  ├─ inadequatetrans.py
│  │  │  ├─ infinitetrans.py
│  │  │  ├─ inkitt.py
│  │  │  ├─ instadoses.py
│  │  │  ├─ isekaiscan.py
│  │  │  ├─ isekaiscaneu.py
│  │  │  ├─ isotls.py
│  │  │  └─ snowycodex.py
│  │  ├─ j
│  │  │  ├─ jpmtl.py
│  │  │  └─ justatrans.py
│  │  ├─ k
│  │  │  ├─ kingmanga.py
│  │  │  ├─ kissmanga.py
│  │  │  ├─ kissnovel.py
│  │  │  ├─ kitenovel.py
│  │  │  ├─ kolnovelnewsite.py
│  │  │  └─ koreanmtl.py
│  │  ├─ l
│  │  │  ├─ ladybirdtrans.py
│  │  │  ├─ latestnovel.py
│  │  │  ├─ lazygirltranslations.py
│  │  │  ├─ lemontree.py
│  │  │  ├─ librarynovel.py
│  │  │  ├─ lightnovelbastion.py
│  │  │  ├─ lightnovelheaven.py
│  │  │  ├─ lightnovelkiss.py
│  │  │  ├─ lightnovelme.py
│  │  │  ├─ lightnovelmeta.py
│  │  │  ├─ lightnovelonline.py
│  │  │  ├─ lightnovelpub.py
│  │  │  ├─ lightnovelreader.py
│  │  │  ├─ lightnovelshub.py
│  │  │  ├─ lightnovelsonl.py
│  │  │  ├─ lightnoveltv.py
│  │  │  ├─ lightnovelworld.com.py
│  │  │  ├─ lightnovelworld.py
│  │  │  ├─ lightnovetrans.py
│  │  │  ├─ listnovel.py
│  │  │  ├─ lnmtl.py
│  │  │  ├─ ltnovel.py
│  │  │  ├─ luminarynovels.py
│  │  │  └─ lunarletters.py
│  │  ├─ m
│  │  │  ├─ machinetransorg.py
│  │  │  ├─ manga-tx.py
│  │  │  ├─ mangabuddy.py
│  │  │  ├─ mangachilllove.py
│  │  │  ├─ mangaread.py
│  │  │  ├─ mangarockteam.py
│  │  │  ├─ mangarosie.py
│  │  │  ├─ mangastic.py
│  │  │  ├─ mangatoon.py
│  │  │  ├─ mangatx.py
│  │  │  ├─ mangaweebs.py
│  │  │  ├─ manhuaplus.py
│  │  │  ├─ manhwachill.py
│  │  │  ├─ meownovel.py
│  │  │  ├─ miraslation.py
│  │  │  ├─ mixednovel.py
│  │  │  ├─ mltnovels.py
│  │  │  ├─ mostnovel.py
│  │  │  ├─ mtlednovels.py
│  │  │  ├─ mtlnation.py
│  │  │  ├─ mtlreader.py
│  │  │  ├─ myboxnovel.py
│  │  │  ├─ myoniyonitrans.py
│  │  │  └─ mysticalmerries.py
│  │  ├─ n
│  │  │  ├─ neosekaitranslations.py
│  │  │  ├─ newnovelorg.py
│  │  │  ├─ newsnovel.py
│  │  │  ├─ noblemtl.py
│  │  │  ├─ noobchan.py
│  │  │  ├─ novel-bin.net.py
│  │  │  ├─ novel-bin.py
│  │  │  ├─ novel27.py
│  │  │  ├─ novel35.py
│  │  │  ├─ novelall.py
│  │  │  ├─ novelbin.net.py
│  │  │  ├─ novelbin.py
│  │  │  ├─ novelcake.py
│  │  │  ├─ novelcool.py
│  │  │  ├─ novelcrush.py
│  │  │  ├─ novelfull.py
│  │  │  ├─ novelfullme.py
│  │  │  ├─ novelfullplus.py
│  │  │  ├─ novelgate.py
│  │  │  ├─ novelhall.py
│  │  │  ├─ novelhard.py
│  │  │  ├─ novelhi.py
│  │  │  ├─ novelhulk.py
│  │  │  ├─ novelhunters.py
│  │  │  ├─ novelmao.py
│  │  │  ├─ novelmic.py
│  │  │  ├─ novelmt.py
│  │  │  ├─ novelmtl.py
│  │  │  ├─ novelmultiverse.py
│  │  │  ├─ novelnext.py
│  │  │  ├─ novelonlinefree.py
│  │  │  ├─ novelonlinefull.py
│  │  │  ├─ novelpassion.py
│  │  │  ├─ novelplanet.py
│  │  │  ├─ novelpub.py
│  │  │  ├─ novelraw.py
│  │  │  ├─ novelsala.py
│  │  │  ├─ novelsemperor.py
│  │  │  ├─ novelsite.py
│  │  │  ├─ novelsonline.py
│  │  │  ├─ novelspl.py
│  │  │  ├─ novelspread.py
│  │  │  ├─ novelsrock.py
│  │  │  ├─ noveltranslate.py
│  │  │  ├─ noveluniverse.py
│  │  │  ├─ novelupdatescc.py
│  │  │  ├─ novelv.py
│  │  │  ├─ novelww.py
│  │  │  ├─ novelzec.py
│  │  │  └─ nyxtranslation.py
│  │  ├─ o
│  │  │  ├─ omgnovels.py
│  │  │  ├─ oppatrans.py
│  │  │  ├─ oppatranslations.py
│  │  │  ├─ ornovel.py
│  │  │  └─ overabook.py
│  │  ├─ p
│  │  │  ├─ pandamanga.py
│  │  │  ├─ pandanovelorg.py
│  │  │  ├─ peryinfo.py
│  │  │  ├─ pianmanga.py
│  │  │  └─ puretl.py
│  │  ├─ q
│  │  │  └─ qidianunderground.py
│  │  ├─ r
│  │  │  ├─ randomnovel.py
│  │  │  ├─ ranobes.py
│  │  │  ├─ readlightnovelcc.py
│  │  │  ├─ readlightnovelorg.py
│  │  │  ├─ readlightnovelsnet.py
│  │  │  ├─ readmanganato.py
│  │  │  ├─ readmtl.py
│  │  │  ├─ readnovelfull.py
│  │  │  ├─ readnovelz.py
│  │  │  ├─ readonlinenovels.py
│  │  │  ├─ readwebnovels.py
│  │  │  ├─ readwn.py
│  │  │  ├─ reaperscans.py
│  │  │  ├─ rebirthonline.py
│  │  │  ├─ reincarnationpalace.py
│  │  │  ├─ relibrary.py
│  │  │  ├─ royalroad.py
│  │  │  └─ rpgnovels.py
│  │  ├─ s
│  │  │  ├─ scribblehub.py
│  │  │  ├─ secondlifetranslations.py
│  │  │  ├─ shalvation.py
│  │  │  ├─ shanghaifantasy.py
│  │  │  ├─ shinsori.py
│  │  │  ├─ skydemonorder.py
│  │  │  ├─ skynovel.py
│  │  │  ├─ sleepytrans.py
│  │  │  ├─ smnovels.py
│  │  │  ├─ steambun.py
│  │  │  ├─ supernovel.py
│  │  │  └─ systemtranslation.py
│  │  ├─ t
│  │  │  ├─ tamagotl.py
│  │  │  ├─ tapread.py
│  │  │  ├─ teanovel.py
│  │  │  ├─ tigertranslations.py
│  │  │  ├─ tipnovel.py
│  │  │  ├─ tomotrans.py
│  │  │  ├─ toonily.py
│  │  │  ├─ topmanhua.py
│  │  │  ├─ totallytranslations.py
│  │  │  ├─ translateindo.py
│  │  │  ├─ travistranslations.py
│  │  │  └─ tunovelaligera.py
│  │  ├─ u
│  │  │  └─ usefulnovel.py
│  │  ├─ v
│  │  │  ├─ veratales.py
│  │  │  ├─ viewnovel.py
│  │  │  ├─ vipnovel.py
│  │  │  ├─ virlyce.py
│  │  │  ├─ vistrans.py
│  │  │  └─ volarenovels.py
│  │  ├─ w
│  │  │  ├─ wanderinginn.py
│  │  │  ├─ webnovel.py
│  │  │  ├─ webnovelonlinecom.py
│  │  │  ├─ webnovelonlinenet.py
│  │  │  ├─ webnovelpub.py
│  │  │  ├─ whatsawhizzerwebnovels.py
│  │  │  ├─ whitemoonlightnovels.py
│  │  │  ├─ wnmtl.py
│  │  │  ├─ wondernovels.py
│  │  │  ├─ woopread.py
│  │  │  ├─ wordexcerpt.py
│  │  │  ├─ wordrain.py
│  │  │  ├─ writerupdates.py
│  │  │  ├─ wspadancewichita.py
│  │  │  ├─ wujizun.py
│  │  │  ├─ wuxiablog.py
│  │  │  ├─ wuxiacity.py
│  │  │  ├─ wuxiaclick.py
│  │  │  ├─ wuxiaco.py
│  │  │  ├─ wuxiacom.py
│  │  │  ├─ wuxiahub.py
│  │  │  ├─ wuxialeague.py
│  │  │  ├─ wuxiamtl.py
│  │  │  ├─ wuxianovelhub.py
│  │  │  ├─ wuxiaonline.py
│  │  │  ├─ wuxiapub.py
│  │  │  ├─ wuxiar.py
│  │  │  ├─ wuxiasite.py
│  │  │  ├─ wuxiau.py
│  │  │  ├─ wuxiav.py
│  │  │  ├─ wuxiaworldio.py
│  │  │  ├─ wuxiaworldlive.py
│  │  │  ├─ wuxiaworldsite.py
│  │  │  ├─ wuxiax.py
│  │  │  └─ wuxiaz.py
│  │  ├─ x
│  │  │  └─ xiainovel.py
│  │  └─ z
│  │     ├─ zenithnovels.py
│  │     ├─ zetrotranslation.py
│  │     ├─ zinmanga.py
│  │     └─ zinnovel.py
│  ├─ es
│  │  └─ domentranslations.py
│  ├─ fr
│  │  ├─ animesama.py
│  │  ├─ chireads.py
│  │  ├─ lightnovelfr.py
│  │  ├─ lnmtlfr.py
│  │  ├─ noveldeglace.py
│  │  └─ xiaowaz.py
│  ├─ id
│  │  ├─ darktrans.py
│  │  ├─ grensia_blogspot.py
│  │  ├─ idqidian.py
│  │  ├─ indomtl.py
│  │  ├─ indowebnovel.py
│  │  ├─ meionovel.py
│  │  ├─ morenovel.py
│  │  ├─ novelgo.py
│  │  ├─ novelku.py
│  │  ├─ novelringan.py
│  │  ├─ noveltoon.py
│  │  ├─ wbnovel.py
│  │  ├─ webnovelindonesia.py
│  │  ├─ webnovelover.py
│  │  ├─ worldnovelonline.py
│  │  ├─ yukinovel.py
│  │  └─ zhiend.py
│  ├─ jp
│  │  └─ s
│  │     └─ syosetu.py
│  ├─ multi
│  │  ├─ foxaholic.py
│  │  ├─ mtlnovel.py
│  │  ├─ novelupdates.py
│  │  ├─ quotev.py
│  │  ├─ wattpad.py
│  │  ├─ webfic.py
│  │  └─ wtrlab.py
│  ├─ pt
│  │  ├─ blnovels.py
│  │  ├─ centralnovel.py
│  │  └─ ceunovel.py
│  ├─ ru
│  │  ├─ bestmanga.py
│  │  ├─ ifreedom.py
│  │  ├─ jaomix.py
│  │  ├─ litnet.py
│  │  ├─ ranobelib.py
│  │  └─ rulate.py
│  ├─ vi
│  │  ├─ lnhakone.py
│  │  └─ truenfull.py
│  └─ zh
│     ├─ 69shuba.py
│     ├─ daocaorenshuwu.py
│     ├─ ixdzs.py
│     ├─ shw5.py
│     ├─ soxs.py
│     ├─ trxs.py
│     ├─ uukanshu.py
│     ├─ uukanshu_sj.py
│     └─ xbanxia.py
└─ .git
   ├─ description
   ├─ hooks
   │  ├─ applypatch-msg.sample
   │  ├─ commit-msg.sample
   │  ├─ fsmonitor-watchman.sample
   │  ├─ post-update.sample
   │  ├─ pre-applypatch.sample
   │  ├─ pre-commit.sample
   │  ├─ pre-merge-commit.sample
   │  ├─ pre-push.sample
   │  ├─ pre-rebase.sample
   │  ├─ pre-receive.sample
   │  ├─ prepare-commit-msg.sample
   │  ├─ push-to-checkout.sample
   │  ├─ sendemail-validate.sample
   │  └─ update.sample
   ├─ info
   │  └─ exclude
   ├─ refs
   │  ├─ heads
   │  └─ tags
   ├─ HEAD
   ├─ config
   └─ objects
      ├─ pack
      └─ info

```