<script>
	import "../../app.css";
  import { Robloxstudio, Roblox, Github, Twitch, Discord, Youtube, X, Reddit, Openai, Sharex, Bitwarden } from "@inqling/svelte-icons/simple-icons";
  import { Envelope, BugAnt, Wifi, Link, LockClosed, Folder } from "@inqling/svelte-icons/heroicon-24-solid"
  import { Badge } from 'flowbite-svelte';
</script>

  <svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
  </svelte:head>


  <div class="w-screen h-screen bg-gray-900 flex items-center">
    <div class="text-left text-white font-roboto font-light pl-16">
      <div>
        <h1 class="text-6xl mb-2.5">Links / Contact</h1>
        <hr class="mb-5">
      </div>
      <div class="flex">
        <div>
          <a href="https://google.com/">
            <div class="text-md mb-4 flex">
              <Robloxstudio class="icon w-8 mr-1" />
              <div class="ml-1">
                <p class="font-bold">Roblox Devforum</p>
                <p>NotMonkeyBusiness</p>
              </div>
            </div>
          </a>
          <a href="https://github.com/TomerJ">
            <div class="text-md mb-4 flex">
              <Github class="icon w-8 mr-1" />
              <div class="ml-1">
                <p class="font-bold">Github</p>
                <p>TomerJ</p>
              </div>
            </div>
          </a>
          <a href="https://google.com/">
            <div class="text-md mb-4 flex">
              <Discord class="icon w-8 mr-1" />
              <div class="ml-1">
                <p class="font-bold">Discord</p>
                <p>notmonkeybusiness</p>
              </div>
            </div>
          </a>
          <a href="https://google.com/">
            <div class="text-md mb-4 flex">
              <Twitch class="icon w-8 mr-1" />
              <div class="ml-1">
                <p class="font-bold">Twitch</p>
                <p>notmonkeybusiness</p>
              </div>
            </div>
          </a>
          <a href="https://google.com/">
            <div class="text-md mb-4 flex">
              <Roblox class="icon w-8 mr-1" />
              <div class="ml-1">
                <p class="font-bold">Roblox</p>
                <p>NotMonkeyBusiness</p>
              </div>
            </div>
          </a>
        </div>
        <div class="ml-8">
          <a href="https://github.com/TomerJ">
            <div class="text-md mb-4 flex">
              <X class="icon w-8 mr-1" />
              <div class="ml-1">
                <p class="font-bold">X / Twitter</p>
                <p>TomerJ</p>
              </div>
            </div>
          </a>
          <a href="https://google.com/">
            <div class="text-md mb-4 flex">
              <Youtube class="icon w-8 mr-1" />
              <div class="ml-1">
                <p class="font-bold">Youtube</p>
                <p>notmonkeybusiness</p>
              </div>
            </div>
          </a>
          <a href="https://google.com/">
            <div class="text-md mb-4 flex">
              <Reddit class="icon w-8 mr-1" />
              <div class="ml-1">
                <p class="font-bold">Reddit</p>
                <p>notmonkeybusiness</p>
              </div>
            </div>
          </a>
          <a href="https://google.com/">
            <div class="text-md mb-4 flex">
              <Envelope class="icon w-8 mr-1" />
              <div class="ml-1">
                <p class="font-bold">Email</p>
                <p>hello@monkeybusiness.dev</p>
              </div>
            </div>
          </a>
          <a href="https://google.com/">
            <div class="text-md mb-4 flex">
              <Wifi class="icon w-8 mr-1" />
              <div class="ml-1">
                <p class="font-bold">Server Status</p>
                <p>status.monkeybusiness.dev</p>
              </div>
            </div>
          </a>



        </div>

        
        <div class="ml-8">
          <a href="https://github.com/TomerJ">
            <div class="text-md mb-4 flex">
              <BugAnt class="icon w-8 mr-1" />
              <div class="ml-1">
                <p class="font-bold">Bug Reports</p>
                <p>bugs.monkeybusiness.dev</p>
              </div>
            </div>
          </a>
          <a href="https://google.com/">
            <div class="text-md mb-4 flex">
              <Openai class="icon w-8 mr-1" />
              <div class="ml-1">
                <p class="font-bold">Free ChatGPT</p>
                <p>chat.monkeybusiness.dev</p>
              </div>
            </div>
          </a>
          <a href="https://google.com/">
            <div class="text-md mb-4 flex">
              <Folder class="icon w-8 mr-1" />
              <div class="ml-1">
                <div class="flex">
                  <p class="font-bold mr-2">File Host</p>
                  <Badge border color="red">
                    <LockClosed class="w-2.5 h-2.5 mr-1.5" />
                    PRIVATE
                  </Badge>
                </div>
                <p>files.monkeybusiness.dev</p>
              </div>
            </div>
          </a>
          <a href="https://google.com/">
            <div class="text-md mb-4 flex">
              <Link class="icon w-8 mr-1" />
              <div class="ml-1">
                <div class="flex">
                  <p class="font-bold mr-2">URL Shortener</p>
                  <Badge border color="red">
                    <LockClosed class="w-2.5 h-2.5 mr-1.5" />
                    PRIVATE
                  </Badge>
                </div>
                <p>urls.monkeybusiness.dev</p>
              </div>
            </div>
          </a>
          <a href="https://google.com/">
            <div class="text-md mb-4 flex">
              <Sharex class="icon w-8 mr-1" />
              <div class="ml-1">
                <div class="flex">
                  <p class="font-bold mr-2">ShareX Server</p>
                  <Badge border color="red">
                    <LockClosed class="w-2.5 h-2.5 mr-1.5" />
                    PRIVATE
                  </Badge>
                </div>
                <p>sharex.monkeybusiness.dev</p>
              </div>

            </div>
          </a>
          
        </div>
        <div class="ml-8">
          <a href="https://github.com/TomerJ">
            <div class="text-md mb-4 flex">
              <Bitwarden class="icon w-8 mr-1" />
              <div class="ml-1">
                <div class="flex">
                  <p class="font-bold mr-2">Bitwarden</p> 
                  <Badge border color="red">
                    <LockClosed class="w-2.5 h-2.5 mr-1.5" />
                    PRIVATE
                  </Badge>
                </div>
                <p>bitwarden.monkeybusiness.dev</p>
              </div>
            </div>
          </a>
        </div>
      </div>
      
    </div>
  </div>