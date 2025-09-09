# WebApplicationGymlit

V tomto krátkém dokumentu si ukážeme, jak si "připravit PC" pro vývoj webové aplikace s `version control` skrze `GIT`

## Instalace a nastavení `GIT`:
1. Zkontrolujeme si, zdali již máme `GIT` nainstalovaný na našem systému:\
    1. Otevřeme příkazový řádek: Stiskneme na klávesnici klávesu se symbolem `WINDOWS` a do nově otevřeného pole napíšeme `cmd` a stiskneme `ENTER`.
    2. Otevře se nám příkazový řádek, do kterého napíšeme příkaz: `git -v`. Tento příkaz by vám měl vypsat vaši konkrétní nainstalovanou verzi `GIT`. 
        Výstup může vypadat například takto: `git version 2.49.0.windows.1`.
    3. Pokud jste si ověřili, že již máte `GIT` nainstalovaný, tak se přesuňte ke kroku 3.
2. Pokud `GIT` nemáte nainstalovaný, tak proveďte následující kroky:
    1. Na této adrese si stáhneme `GIT CLI`: https://git-scm.com/downloads/win
    2. Spustíme stažený `EXE` soubor (všechny možnosti necháme "defaultní"), čímž si nainstalujeme `GIT CLI`.
3. Vytvoříme si někde na disku novou složku, která bude "zahrnovat" vaše lokální repozitáře. 
    Jak tu složku můžete pojmenovat je zcela na vás, mě napadá například:
    * `localRepos`
    * `repos`
    * `dev`
    * `CsItGIT`
4. Otevřeme v této složce příkazový řádek: Klikneme na cestu naší složky, což ji označí, a následně napíšeme `cmd` a stiskneme `ENTER`.
5. V příkazové řádce si nejprve nastavíme své údaje:
    * Změna jména: `git config --global user.name "Vaše jméno"`
    * Změna emailu: `git config --global user.email "Váš email"`
    * Zkontrolujte si tyto kroky pomocí: `git config --list`
6. Nyní se přihlaste do svého `GitHub` účtu (pokud ještě nemáte `GitHub`, vytvořte si jej zde: https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home)
7. 