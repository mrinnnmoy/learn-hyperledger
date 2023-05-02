<p>Hyperledger is a private permissioned blockchain.</p>

<p>Issues with public blockchain:</p>
<ul>
    <li>Confidentiality.</li>
    <li>Slow.</li>
    <li>Scalibility.</li>
</ul>

<p>Public VS Private Blockchain.</p>
<table>
  <tr>
    <th>Properties</th>
    <th>Public</th>
    <th>Private</th>
  </tr>
  <tr>
    <td>Decentralize Ledger</td>
    <td>Yes</td>
    <td>Yes</td>
  </tr>
  <tr>
    <td>Same Ledger</td>
    <td>Yes</td>
    <td>No</td>
  </tr>
    <tr>
    <td>Immutable</td>
    <td>Yes</td>
    <td>Yes</td>
  </tr>
    <tr>
    <td>Anonymous</td>
    <td>Yes</td>
    <td>No</td>
  </tr>
    <tr>
    <td>All Node Verification</td>
    <td>Yes</td>
    <td>No</td>
  </tr>
    <tr>
    <td>Smart Contract</td>
    <td>Yes</td>
    <td>Yes</td>
  </tr>
    <tr>
    <td>Transparent</td>
    <td>Yes</td>
    <td>No</td>
  </tr>
</table>

<p>Hyperledger is an umbrella project of open source blockchain and related tools, started in December 2015, by the Linux Foundation.</p>

<h3>Hyperledger Fabric consists of four major components:</h3>
<ul>
    <li>Channel: It is a private communication pathway between two or more members of a hyperledger.
    </li>
    <li>MSP: Member Service Provider is a modular component that is used to manage identities on the blockchain network. This provider is used to authenticate clients who want to join the blockchain network.
    </li>
    <li>Chaincode: It is a program written in Go, Node JS, or Java that implements a prescribed interface.
    </li>
    <li>Access Control List: It is a list of rules that specifies which users or systems are granted or denied access to a particular object or system resource.
    </li>
</ul>

<p>Different types of Nodes:</p>
<ul>
    <li>Commiting Nodes: Nodes that have all the copies of the ledger.</li>
    <li>Endorsing Nodes: Nodes that can execute chain code.</li>
    <li>Ordering Nodes: Nodes that maintain the sequence of transactions.</li>
</ul>

<p>Hyperledger Transaction Flow:</p>

<ul>
    <li>Step 1: Client initiating a transaction.</li>
    <li>Step 2: Validation of transaction.</li>
    <li>Step 3: Simulating the transaction.</li>
    <li>Step 4: Verifying propsal Response.</li>
    <li>Step 5: Broadcast transaction to the orderer.</li>
    <li>Step 6: Order transaction and create block.</li>
    <li>Step 7: Peers validate each transaction in the block.</li>
    <li>Step 8: Committing to the respective ledger.</li>
</ul>