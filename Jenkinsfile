// calling the shared library 
// "i27academy-slb@main" this name is coming from
// jenkins-> manage jenkins -> system -> Global Trusted Pipeline Libraries -> name(i27academy-slb) -> Defualt versin "you git branch" (main/master) -> git -> added shared library repo and save
// "@main" you defualt version in manage jenkins or  git branch of your shared librarys
@Library("i27academy-slb@main") _
    dockerPipeline(
        appName: 'user',
        devPort: '5232',
        testPort: '6232',
        stagePort: '7232',
        prodPort: '8232',
        contPort: '8232'
    )