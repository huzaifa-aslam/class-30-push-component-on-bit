https://docs.bit.dev/docs/tutorials/bit-react-tutorial // documentation link

npm install bit-bin -g // to install bit cli

create an account on bit.dev  //https://bit.dev/

bit init --package-manager yarn

make a component

bit add src/components/helloWorld.jsx(src/<folder-name-which-has-components>/<component-name>)  // to bundle a component

bit import bit.envs/compilers/react --compiler // to install react compiler

bit build // to build components

bit tag --all 0.0.1 // to add tag (0.0.1) vairy version to version

finally

bit export huzaifa-aslam.helloworld (<organization-name>.<collection-name>)

refresh page

click on your component

copy the npm package name like "npm i @bit/huzaifa-aslam.helloworld.hello-world"

npm config set @bit:registry https://node.bit.dev // if u dont have bit and u want run component then install first above command then try

