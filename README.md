# WebApplicationGymlit

Toto `README` je prozatím "nic moc", ale prozatím jej můžeme využít pro zapsání potřebných kroků pro "ovládání `GIT`u":

1. Na této adrese si stáhneme `GIT CLI`: https://git-scm.com/downloads/win
2. Spustíme stažený `EXE` soubor (všechny možnosti necháme "defaultní"), čímž si nainstalujeme `GIT CLI`.
3. Vytvoříme si někde na disku novou složku, která bude "zahrnovat" vaše lokální repozitáře. 
    Jak tu složku můžete pojmenovat je zcela na vás, mě napadá například:
    * `localRepos`
    * `repos`
    * `dev`
    * `CsItGIT`
4. Otevřeme v této složce příkazový řádek. Jak to udělat? Klikneme na cestu naší složky, což ji označí, a následně napíšeme `cmd` a stiskneme `ENTER`.
5. V příkazové řádce si nejprve nastavíme své údaje:
    * Změna jména: `git config --global user.name "Vaše jméno"`
    * Změna emailu: `git config --global user.email "Váš email"`
    * Zkontrolujte si tyto kroky pomocí: `git config --list`