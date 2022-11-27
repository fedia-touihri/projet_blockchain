# projet_blockchain
npx hardhat compile//pour compiler le contrat intelligent ->va creer le dossier artifacts dans /src de react 
//et donc ce dossier dapp2\src\artifacts\contracts\Helloworld.sol\HelloWorld.json ->cest le fichier de "abi" c'est ce qui va nous permettre d'interagir au nioveau de front avec le contrat 
npx hardhat node //deployer ca sur un bmockchain de test(node locale)->va fournir 20 @
npx hardhat run scripts/deploy.ts --network localhost//va fdeployer le contract sur net locale
qu'on va utliser pour interagir avec le frontend 