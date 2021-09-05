# Today I Learned Tracker

##### (Add the date, notes, progress made, and any resources used each day)

### 05/019/2021 install different versions of Java on linux and use update-alternatives

"install" by downloading jdks and then adding

`sudo update-alternatives /usr/bin/java java /usr/lib/jvm/jdk11/bin/java`

and dito for `jar` and `javac`

`sudo update-alternatives --show java`

change java version
`sudo update-alternatives --config java`

[see](https://dev.to/thegroo/install-and-manage-multiple-java-versions-on-linux-using-alternatives-5e93)


### 01/01/2021 Which Tests Should We Automate?

4 criterias made up by 2 factors a,b each, with a,b \in 1..5, a * b = score for criteria

1. Risk = Impact (if broken, what's the impact) x Probability (frequency of use by customer)
2. Value = Case for Action (how quickly would this failure be fixed?) x Distinctness (does this test provide new info?)
3. COST-EFFECIENCY = Ease (how easy will it be to script this) x quickness (how quick can this be scripted)
4. History = Frequency of breaks (volume of historical failures for this test) x Similiar to weak areas (volume of historical failures in related areas)

sum of score: 75-100 automate, 25-74 possible automate, 0-24 don't automate

https://www.youtube.com/watch?v=VL-_pnICmGY https://slides.com/angiejones/which-tests-should-we-automate

### 31/12/2020

**Notes**

using gitlab cd/cd @work

**Progess**

making it work for a small sample repo

### 30/12/2020

**Notes**

`git`: push a branch to remote that does not exist there yet:
```sh
git push -u origin <branch-name>
```


### 27/12/2020

**Notes**

using github "dependabot" as "beta" and directly on github

**Progess**

introduced to some repos

**Link to Code**

[dependabot in synk-v-test](https://github.com/epischel/synk-v-test/blob/master/.github/dependabot.yml)

**Resources Used**

github docs

### 26/12/2020

**Notes**

create a github action for a gradle project. using to "publish" to github pages.

**Progess**

I started building a basic webpage on CodePen 

**Link to Code**

[Github Action YML file](https://github.com/epischel/gensources/blob/main/.github/workflows/publish.yml)

**Resources Used**

github docs

---

## 01/02/2021

**Notes**


**Progess**


**Link to Code**


**Resources Used**



---



