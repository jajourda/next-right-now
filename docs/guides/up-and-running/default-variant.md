---
layout: default
title: Up and Running - E2E > Default Variant
parent: Up and Running - E2E
grand_parent: Guides
nav_order: 10
---

# Default Variant (v1-ssr) > Up and Running - E2E 

<p class="fs-6 fw-300">
This is the <a href="/getting-started/pick-variant#v1-ssr---default-variant">default variant</a>  for Next Right Now (NRN): <strong>v1-ssr</strong> (click <a href="/concepts/variants">here</a> if you don't know what a variant is). It is the main variant at this time. It is also the most complicated and feature-rich, as it contains all available features built-in.
</p>

## Walkthrough Steps

<ol>
   <li class="step">
        <h3>Get Your Environment and Equipment Ready </h3>
        <div class="content">
            <ul>
                <li>Next-right-now is a repo that requires Node.js to be installed on your system.</li>
                <li>You will need a text editor to write code</li>
                <li>You will need a Terminal application to invoke some commands.</li>
            </ul>
            <div class="tip">
                <strong>Environment</strong>
                <p>This project is optimized for Jetbrains Webstorm text-editor. But you can use any text-editor you prefer. (Visual Studio Code is a great, free option.)</p>
            </div>
        </div>
    
   </li>
    <li class="step">
        <h3>Clone this Variant to your Local Machine</h3>
        <div class="content">
            <ol>
                <li>
                    <div class="sub-step">
                        <p>Open a terminal instance in your terminal app and run the following commands.</p>
                        <div class="language-bash highlighter-rouge">
                            <div class="highlight">
                            <pre class="highlight"><code><span class="nb">#Clones the boilerplate</span><br><span class="nv">$ </span>git clone https://github.com/UnlyEd/next-right-now.git <span class="mf">NAME_OF_YOUR_PROJECT</span><br><span class="nb">#Selects the variant</span><br><span class="nv">$ </span><span class="ow">cd </span><span class="mf">NAME_OF_YOUR_PROJECT</span>&& git checkout v1-ssr<br><span class="nb">#Duplicates the .env.build.example as .env.build (.env.build is only used when working locally)</span><br><span class="nv">$ </span>cp .env.build.example .env.build
</code></pre>
                            </div>
                        </div>
                    </div>
                </li>
            </ol>
            <div class="tip">
            {% include installation-guide-tips-html.md %}
            </div>
        </div>
    
   </li>
   <li class="step">
    <h3>Create an account for all required 3rd party vendors</h3>
    <div class="content">
    Create an account for all required 3rd party vendors above, and fill-in missing environment variables in your <code>.env.build</code> file
    <ol>
        <li class="substep">
            <h4>Setup GraphCMS Account</h4>
            <div class="highlight">
                <code class="p-2">
                    <span class="label label-yellow">CMS</span>
                    <span class="label label-red"> (Limited) Freemium</span>
                    <span class="label label-green">GraphQL Approach</span>
                </code>
            </div>
            <div class="content">
                <ol>
                    <li>
                    Sign-up for graphCMS
                    </li>
                    <li>
                    Create a new project within the graphCMS backend gui.
                    <figure>
                        <img src="/assets/images/graphcmscreateproject.jpg" alt="graph cms create project">
                    </figure>
                    </li>
                    <li>
                    Pick the region closest to you. Give your project a name and a description.
                    <figure>
                        <img src="/assets/images/create-new-project-graphcms.jpg" alt="graph cms create project">
                    </figure> 
                    </li>
                    <li>
                    Pick a pricing plan. (I did the free one).
                    <figure>
                    <img src="/assets/images/pick-a-pricing-plan.jpg" alt="">
                    </figure>
                    </li>
                    <li>
                    Configure your GraphCMS project.
                        <figure><img src="/assets/images/configure-your-graphcms-project.jpg" alt=""></figure>
                    </li>
                    <li>
                    Navigate to your project's settings. 
                    <figure><img src="/assets/images/navigate-to-settings.jpg" alt=""></figure>
                    Click on the API Access Settings.
                    <figure><img src="/assets/images/go-to-api-access.jpg" alt=""></figure>
                    </li>
                    <li>
                    Create an authentication token for your Next-righ-now app to access
                        <figure><img src="/assets/images/create-authentication-token-for-api-access.jpg" alt=""></figure>
                    </li>
                    <li>
                        Copy your existing token to the clipboard to paste to the .env.build file.
                        <figure><img src="/assets/images/copy-your-existing-token-to-clipboard-to-paste-to-env-build.jpg" alt=""></figure>
                    </li>
                </ol>
            </div>
        </li>
        <li class="substep">
            <h4>Setup Locize Account</h4>
            <div class="content"></div>
        </li>
        <li class="substep">
            <h4>Setup Sentry Account</h4>
            <div class="content"></div>
        </li>
        <li class="substep">
            <h4>Setup Amplify Account</h4>
            <div class="content"></div>
        </li>
        <li class="substep">
            <h4>Setup Zeit Account</h4>
            <div class="content"></div>
        </li>
    </ol>
    </div>
   </li>
   <li class="step">
        <h3>Setup Local Environment for Development</h3>
        <div class="content">
        <p>Use your text-editor's built-in terminal <strong>or</strong> <code>cd NAME_OF_YOUR_PROJECT</code> and run these commands in your terminal app:</p>
        <div class="language-bash highlighter-rouge">
                            <div class="highlight">
                            <pre class="highlight"><code><span class="nb">#Selects the right node.js version based on the .nvmrc file</span><br><span class="nv">$ </span>nvm use<br><span class="nb">#now@17+ requires to be authenticated to Zeit in order to launch the project locally, so you must use now@16 instead, to avoid additional setup</span><br><span class="nv">$ </span>yarn add -D now@16.7.3 <br><span class="nb">#Installs all deps from package.json</span><br><span class="nv">$ </span>yarn <br><span class="nb">#Starts the app on http://localhost:8888/</span><br><span class="nv">$ </span>yarn start <br>
</code></pre>
                            </div>
                        </div>
        </div>
   </li>
   <li>
   <h3>Make Your First Change to the Codebase</h3>
   <div class="content">
    <p>Create a change in the codebase and watch NRN in action from E2E!</p>
   </div>
   </li>
</ol>
