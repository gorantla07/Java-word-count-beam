https://beam.apache.org/get-started/quickstart-java/

mvn archetype:generate `
  -D archetypeGroupId=org.apache.beam `
  -D archetypeArtifactId=beam-sdks-java-maven-archetypes-examples `
  -D archetypeVersion=2.42.0 `
  -D groupId=org.example `
  -D artifactId=word-count-beam `
  -D version="0.1" `
  -D package=org.apache.beam.examples `
  -D interactiveMode=false
   
cd .\word-count-beam

dir .\src\main\java\org\apache\beam\examples

In the word-count-beam directory, create a file called sample.txt. Add some text to the file. For this example

mvn compile exec:java -D exec.mainClass=org.apache.beam.examples.WordCount `
 -D exec.args="--inputFile=sample.txt --output=counts" -P direct-runner

ls counts*
   
more counts*

Output :

day: 1
shut: 1
rest: 1
send: 1
bestow: 2
consummation: 1
say: 2
can: 2
erthrown: 1
suffers: 1
proud: 2
dost: 1
From: 1
unworthy: 1
part: 1
Where: 1
confession: 1
patient: 1
honey: 1
sea: 1
delay: 1
At: 1
forcing: 1
round: 1
God: 2
I: 32
certain: 1
days: 1
honest: 3
be: 14
drive: 1
merit: 1
right: 1
alone: 1
needs: 1
O: 7
How: 3
die: 2
delights: 1
lack: 1
expectancy: 1
inclined: 1
Tis: 2
prevent: 1
Be: 1
Take: 1
take: 1
crawling: 1
awry: 1
well: 8
espials: 1
youth: 1
hath: 1
Madam: 2
crafty: 1
lawful: 1
have: 14
Good: 2
may: 6
scholar: 1
upon: 1
sweat: 1
content: 1
proved: 1
perchance: 1
troubles: 1
With: 5
relish: 1
action: 2
HAMLET: 13
Whereon: 1
shuffled: 1
make: 5
harshly: 1
raught: 1
Previous: 2
ll: 3
conscience: 2
remembrances: 1
on: 8
speak: 1
oppressor: 1
queen: 1
office: 1
No: 3
dream: 1
believe: 3
fell: 1
expel: 1
homepage: 2
already: 2
beating: 1
SCENE: 1
conference: 1
countries: 1
marry: 3
scene: 4
though: 1
bare: 1
And: 17
must: 1
things: 2
face: 1
escape: 1
mother: 2
speech: 1
bells: 1
Was: 1
lost: 1
name: 2
Nor: 2
does: 3
mortal: 1
deject: 1
sounded: 1
thee: 3
pure: 1
yet: 2
Ophelia: 5
chaste: 1
again: 2
another: 1
transform: 1
know: 3
tongue: 1
commencement: 1
enter: 1
put: 1
Aside: 1
aught: 1
madness: 2
borne: 1
Next: 2
Like: 1
Most: 2
sent: 1
great: 2
Gertrude: 1
