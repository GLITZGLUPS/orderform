# orderform
How to order a custom snow globe tumbler
 <!-- 1. Customer Details -->
  <section class="bg-white rounded-2xl p-6 shadow-sm border border-pink-100">
    <h2 class="text-lg font-bold text-slate-900 mb-4 flex items-center gap-2">
      <span class="bg-pink-100 text-pink-600 w-7 h-7 rounded-full inline-flex items-center justify-center text-sm font-bold">1</span>
      Customer Details
    </h2>
    <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
      <div>
        <label class="block text-xs font-semibold text-slate-600 uppercase mb-1">Full Name & Tiktok Name *</label>
        <input required type="text" id="custName" placeholder="e.g. Briella Leho" 
          class="w-full px-3.5 py-2.5 rounded-xl border border-slate-200 focus:outline-none focus:ring-2 focus:ring-pink-400 focus:border-transparent text-sm">
      </div>
      <div>
        <label class="block text-xs font-semibold text-slate-600 uppercase mb-1">WhatsApp / Phone *</label>
        <input required type="tel" id="custPhone" placeholder="e.g. +60 12-345 6789" 
          class="w-full px-3.5 py-2.5 rounded-xl border border-slate-200 focus:outline-none focus:ring-2 focus:ring-pink-400 focus:border-transparent text-sm">
      </div>
      <div class="sm:col-span-2">
        <label class="block text-xs font-semibold text-slate-600 uppercase mb-1">Delivery Address *</label>
        <textarea required id="custAddress" rows="2" placeholder="Street, City, State, Postcode" 
          class="w-full px-3.5 py-2.5 rounded-xl border border-slate-200 focus:outline-none focus:ring-2 focus:ring-pink-400 focus:border-transparent text-sm"></textarea>
      </div>
    </div>
  </section>

  <!-- 2. Tumbler Base & Size -->
  <section class="bg-white rounded-2xl p-6 shadow-sm border border-pink-100">
    <h2 class="text-lg font-bold text-slate-900 mb-2 flex items-center gap-2">
      <span class="bg-pink-100 text-pink-600 w-7 h-7 rounded-full inline-flex items-center justify-center text-sm font-bold">2</span>
      Choose Your Tumbler Base
    </h2>
    <p class="text-xs text-slate-500 mb-4"> All tumbler price are include effect solution with mica.</p>
    
    <div class="grid grid-cols-1 sm:grid-cols-3 gap-3">
      <div>
        <input type="radio" id="tumbler16oz" name="tumblerBase" value="16oz Acrylic Tumbler" data-price="26" class="hidden" checked onchange="updateTotal()">
        <label for="tumbler16oz" class="block p-4 rounded-xl border-2 border-slate-200 cursor-pointer transition text-center hover:border-pink-300">
          <span class="font-bold text-slate-800 text-sm block">10oz Kid Tumbler</span>
          <span class="text-xs text-slate-500 block mb-2">Flip Straw</span>
          <span class="font-semibold text-pink-600 text-sm">RM 38.00</span>
        </label>
      </div>
      <div>
        <input type="radio" id="tumbler24oz" name="tumblerBase" value="24oz Venti Acrylic" data-price="32" class="hidden" onchange="updateTotal()">
        <label for="tumbler24oz" class="block p-4 rounded-xl border-2 border-slate-200 cursor-pointer transition text-center hover:border-pink-300">
          <span class="font-bold text-slate-800 text-sm block">16oz Clear Lid</span>
          <span class="text-xs text-slate-500 block mb-2">without handle</span>
          <span class="font-semibold text-pink-600 text-sm">RM 42.00</span>
        </label>
      </div>
      <div>
        <input type="radio" id="tumblerCan" name="tumblerBase" value="16oz Beer Can Glass (Bamboo Lid)" data-price="35" class="hidden" onchange="updateTotal()">
        <label for="tumblerCan" class="block p-4 rounded-xl border-2 border-slate-200 cursor-pointer transition text-center hover:border-pink-300">
          <span class="font-bold text-slate-800 text-sm block">16oz Clear Lid</span>
          <span class="text-xs text-slate-500 block mb-2"> With Handle</span>
          <span class="font-semibold text-pink-600 text-sm">RM 45.00 </span>
        </label>
      </div>
    </div>
        <input type="radio" id="tumblerCan" name="tumblerBase" value="16oz Beer Can Glass (Bamboo Lid)" data-price="35" class="hidden" onchange="updateTotal()">
        <label for="tumblerCan" class="block p-4 rounded-xl border-2 border-slate-200 cursor-pointer transition text-center hover:border-pink-300">
          <span class="font-bold text-slate-800 text-sm block">18oz Leak Proof Cup</span>
          <span class="text-xs text-slate-500 block mb-2"> Secure Lid</span>
          <span class="font-semibold text-pink-600 text-sm">RM 48.00 </span>
        </label>
      </div>
    </div>
    <div class="grid grid-cols-1 sm:grid-cols-3 gap-3">
      <div>
        <input type="radio" id="tumbler16oz" name="tumblerBase" value="16oz Acrylic Tumbler" data-price="26" class="hidden" checked onchange="updateTotal()">
        <label for="tumbler16oz" class="block p-4 rounded-xl border-2 border-slate-200 cursor-pointer transition text-center hover:border-pink-300">
          <span class="font-bold text-slate-800 text-sm block">24oz Clear Lid Tumbler</span>
          <span class="text-xs text-slate-500 block mb-2">Screw Lid</span>
          <span class="font-semibold text-pink-600 text-sm">RM 52.00</span>
        </label>
      </div>
      <div>
        <input type="radio" id="tumbler24oz" name="tumblerBase" value="24oz Venti Acrylic" data-price="32" class="hidden" onchange="updateTotal()">
        <label for="tumbler24oz" class="block p-4 rounded-xl border-2 border-slate-200 cursor-pointer transition text-center hover:border-pink-300">
          <span class="font-bold text-slate-800 text-sm block">40oz Tumbler</span>
          <span class="text-xs text-slate-500 block mb-2">Clear Lid</span>
          <span class="font-semibold text-pink-600 text-sm">RM 65.00</span>
        </label>
      </div>
      <div>
        <input type="radio" id="tumblerCan" name="tumblerBase" value="16oz Beer Can Glass (Bamboo Lid)" data-price="35" class="hidden" onchange="updateTotal()">
        <label for="tumblerCan" class="block p-4 rounded-xl border-2 border-slate-200 cursor-pointer transition text-center hover:border-pink-300">
          <span class="font-bold text-slate-800 text-sm block">20oz Stainless Steel</span>
          <span class="text-xs text-slate-500 block mb-2"> Without Handle</span>
          <span class="font-semibold text-pink-600 text-sm">RM 65.00 </span>
        </label>
      </div>
    </div>
        <input type="radio" id="tumblerCan" name="tumblerBase" value="16oz Beer Can Glass (Bamboo Lid)" data-price="35" class="hidden" onchange="updateTotal()">
        <label for="tumblerCan" class="block p-4 rounded-xl border-2 border-slate-200 cursor-pointer transition text-center hover:border-pink-300">
          <span class="font-bold text-slate-800 text-sm block">20oz Stainless Steel</span>
          <span class="text-xs text-slate-500 block mb-2"> With Handle</span>
          <span class="font-semibold text-pink-600 text-sm">RM 65.00 </span>
        </label>
      </div>
    </div>
    <div class="grid grid-cols-1 sm:grid-cols-3 gap-3">
      <div>
        <input type="radio" id="tumbler16oz" name="tumblerBase" value="16oz Acrylic Tumbler" data-price="26" class="hidden" checked onchange="updateTotal()">
        <label for="tumbler16oz" class="block p-4 rounded-xl border-2 border-slate-200 cursor-pointer transition text-center hover:border-pink-300">
          <span class="font-bold text-slate-800 text-sm block">24oz Curve Tumbler</span>
          <span class="text-xs text-slate-500 block mb-2">Flip Straw</span>
          <span class="font-semibold text-pink-600 text-sm">RM 48.00</span>
        </label>
    <div class="grid grid-cols-1 sm:grid-cols-3 gap-3">
      <div>
        <input type="radio" id="tumbler16oz" name="tumblerBase" value="16oz Acrylic Tumbler" data-price="26" class="hidden" checked onchange="updateTotal()">
        <label for="tumbler16oz" class="block p-4 rounded-xl border-2 border-slate-200 cursor-pointer transition text-center hover:border-pink-300">
          <span class="font-bold text-slate-800 text-sm block">24oz Boba Top Tumbler</span>
          <span class="text-xs text-slate-500 block mb-2">Secure Lid</span>
          <span class="font-semibold text-pink-600 text-sm">RM 55.00</span>
        </label>

</section>

  <!-- 3. Choose Your Decals/Sticker -->
  <section class="bg-white rounded-2xl p-6 shadow-sm border border-pink-100">
    <h2 class="text-lg font-bold text-slate-900 mb-2 flex items-center gap-2">
      <span class="bg-pink-100 text-pink-600 w-7 h-7 rounded-full inline-flex items-center justify-center text-sm font-bold">3</span>
      Decals/Sticker 
    </h2>
    
    <!-- Decals Types -->
    <div class="mb-4">
      <label class="block text-xs font-semibold text-slate-600 uppercase mb-2">Decals/Sticker</label>
      <div class="grid grid-cols-2 sm:grid-cols-4 gap-2 text-xs">

    </div>

    <!-- Decals Palette Price-->
    <div class="mb-4">
      <label class="block text-xs font-semibold text-slate-600 uppercase mb-2">Pick One</label>
      <select id="glitterColor" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-200 text-sm focus:outline-none focus:ring-2 focus:ring-pink-400">
        <option value="16oz size"> No Sticker</option>
        <option value="16oz size"> 16oz Sticker RM13</option>
        <option value="16oz size"> 16oz Sticker RM15</option>
        <option value="20oz size"> 20oz Sticker RM16</option>
        <option value="24oz size"> 24oz Sticker RM18</option>
        <option value="24oz size"> 40oz Sticker RM18</option>
       </select>
    </div>

</section>

  <!-- 5. Flow Style -->
  <section class="bg-white rounded-2xl p-6 shadow-sm border border-pink-100">
    <h2 class="text-lg font-bold text-slate-900 mb-2 flex items-center gap-2">
      <span class="bg-pink-100 text-pink-600 w-7 h-7 rounded-full inline-flex items-center justify-center text-sm font-bold">4</span>
     Effect Solution/Flow Physics
    </h2>
    

    <!-- Effect Solution Palette -->
    <div class="mb-4">
      <label class="block text-xs font-semibold text-slate-600 uppercase mb-2">Effect Solution</label>
      <select id="effectsolution" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-200 text-sm focus:outline-none focus:ring-2 focus:ring-pink-400">
        <option value="Single Lava"> Single Lava</option>
        <option value="Dual Lava"> Dual Lava</option>
        <option value="Invisible Lava"> Invisible Lava</option>
        <option value="Reverse Lava"> Reverse Lava</option>
        <option value="Floral Theme"> Floral Theme</option>
        <option value="Beach Theme"> Beach Theme</option>
        <option value="Cat Eye"> Cat Eye RM 6</option>   
        <option value="Full Glitter"> Full Glitter RM 10</option>      
      </select>
    </div>

</section>

  <!-- 5. Add In -->
  <section class="bg-white rounded-2xl p-6 shadow-sm border border-pink-100">
    <h2 class="text-lg font-bold text-slate-900 mb-2 flex items-center gap-2">
      <span class="bg-pink-100 text-pink-600 w-7 h-7 rounded-full inline-flex items-center justify-center text-sm font-bold">5</span>
      Add-Ins 
    </h2>
    
    <!-- Glitter Types -->
    <div class="mb-4">
      <label class="block text-xs font-semibold text-slate-600 uppercase mb-2">Add Ins (Pick up to 3 each options)</label>
      <div class="grid grid-cols-2 sm:grid-cols-4 gap-2 text-xs">
        <label class="flex items-center gap-2 p-2.5 rounded-lg border border-slate-200 cursor-pointer hover:bg-slate-50">
          <input type="checkbox" name="glitterType" value="Fine Glitter" class="rounded text-pink-500"> Fine Glitter +RM8
        </label>
        <label class="flex items-center gap-2 p-2.5 rounded-lg border border-slate-200 cursor-pointer hover:bg-slate-50">
          <input type="checkbox" name="glitterType" value="Chunky Glitter" class="rounded text-pink-500" checked> Chunky Glitter +RM10
        </label>
        <label class="flex items-center gap-2 p-2.5 rounded-lg border border-slate-200 cursor-pointer hover:bg-slate-50">
          <input type="checkbox" name="glitterType" value="Polymer Clay" class="rounded text-pink-500"> Polymer Clay +RM8
        </label>
        <label class="flex items-center gap-2 p-2.5 rounded-lg border border-slate-200 cursor-pointer hover:bg-slate-50">
          <input type="checkbox" name="glitterType" value="Rhinestones" class="rounded text-pink-500"> Rhinestones +RM10
          </label>
</section>
        <label class="flex items-center gap-2 p-2.5 rounded-lg border border-slate-200 cursor-pointer hover:bg-slate-50">
          <input type="checkbox" name="glitterType" value="Glow in The Dark" class="rounded text-pink-500"> Glow in The Dark Glitter +RM8
        </label>
        <label class="flex items-center gap-2 p-2.5 rounded-lg border border-slate-200 cursor-pointer hover:bg-slate-50">
          <input type="checkbox" name="glitterType" value="Dried Flower" class="rounded text-pink-500"> Dried Flower +RM10
        </label>
        <label class="flex items-center gap-2 p-2.5 rounded-lg border border-slate-200 cursor-pointer hover:bg-slate-50">
          <input type="checkbox" name="glitterType" value="Shell Gravel" class="rounded text-pink-500"> Shell Gravel +RM8
        </label>
        <label class="flex items-center gap-2 p-2.5 rounded-lg border border-slate-200 cursor-pointer hover:bg-slate-50">
          <input type="checkbox" name="glitterType" value="Sand" class="rounded text-pink-500"> Sand +RM12
        </label>
      </div>
    </div>

  </section>

  <!-- 6.   Add Ons -->
  <section class="bg-white rounded-2xl p-6 shadow-sm border border-pink-100">
    <h2 class="text-lg font-bold text-slate-900 mb-2 flex items-center gap-2">
      <span class="bg-pink-100 text-pink-600 w-7 h-7 rounded-full inline-flex items-center justify-center text-sm font-bold">6</span>
      Add-Ons & Personalization
    </h2>

        <label class="block text-xs font-semibold text-slate-600 uppercase mb-1">Custom Name / Monogram</label>
        <input type="text" id="customNameInput" placeholder="e.g. Briella/B" 
          class="w-full px-3.5 py-2.5 rounded-xl border border-slate-200 focus:outline-none focus:ring-2 focus:ring-pink-400 text-sm"
          oninput="renderFontPreview()">
      </div>
    </div>

  </section>

  <!-- 7. Add-Ons & Extras -->
  <section class="bg-white rounded-2xl p-6 shadow-sm border border-pink-100">
    <h2 class="text-lg font-bold text-slate-900 mb-3 flex items-center gap-2">
      <span class="bg-pink-100 text-pink-600 w-7 h-7 rounded-full inline-flex items-center justify-center text-sm font-bold">7</span>
      Handcrafted Add-Ons
    </h2>
    <div class="space-y-2.5">
      <label class="flex items-center justify-between p-3.5 rounded-xl border border-slate-200 cursor-pointer hover:bg-slate-50">
        <div class="flex items-center gap-3">
          <input type="checkbox" name="addons" value="Rhinestone Lid" data-price="18" onchange="updateTotal()" class="rounded text-pink-500 w-4 h-4">
          <div>
            <span class="font-medium text-slate-800 text-sm block"> Full Rhinestone</span>
            <span class="text-xs text-slate-500"> For 16oz Only</span>
          </div>
        </div>
        <span class="font-semibold text-slate-700 text-sm">+RM18.00</span>
</label>

      <label class="flex items-center justify-between p-3.5 rounded-xl border border-slate-200 cursor-pointer hover:bg-slate-50">
        <div class="flex items-center gap-3">
          <input type="checkbox" name="addons" value="Ice Deco Resin Lid" data-price="5" onchange="updateTotal()" class="rounded text-pink-500 w-4 h-4">
          <div>
            <span class="font-medium text-slate-800 text-sm block"> Ice Deco</span>
            <span class="text-xs text-slate-500">Resin Lid</span>
          </div>
        </div>
        <span class="font-semibold text-slate-700 text-sm">+RM18.00</span>
      </label>

      <label class="flex items-center justify-between p-3.5 rounded-xl border border-slate-200 cursor-pointer hover:bg-slate-50">
        <div class="flex items-center gap-3">
          <input type="checkbox" name="addons" value="Full Resin Matching Glitter Blend Lid" data-price="5" onchange="updateTotal()" class="rounded text-pink-500 w-4 h-4">
          <div>
            <span class="font-medium text-slate-800 text-sm block"> Full Resin </span>
            <span class="text-xs text-slate-500">Matching Glitter Blend Lid</span>
          </div>
        </div>
        <span class="font-semibold text-slate-700 text-sm">+RM10.00</span>
      </label>
      <label class="flex items-center justify-between p-3.5 rounded-xl border border-slate-200 cursor-pointer hover:bg-slate-50">
        <div class="flex items-center gap-3">
          <input type="checkbox" name="addons" value="Dangling Beaded Keychain" data-price="6" onchange="updateTotal()" class="rounded text-pink-500 w-4 h-4">
          <div>
            <span class="font-medium text-slate-800 text-sm block">Dangling</span>
            <span class="text-xs text-slate-500">Beaded keychain</span>
          </div>
        </div>
        <span class="font-semibold text-slate-700 text-sm">+RM15.00</span>
      </label>
    </div>

    <div class="mt-4">
      <label class="block text-xs font-semibold text-slate-600 uppercase mb-1">Special Instructions or Custom Requests</label>
      <textarea id="specialNotes" rows="2" placeholder="e.g. Please add extra pink stars and heavy slow-flow solution..." 
        class="w-full px-3.5 py-2.5 rounded-xl border border-slate-200 focus:outline-none focus:ring-2 focus:ring-pink-400 text-sm"></textarea>
    </div>
  </section>

  <!-- Submit & Price Summary -->
  <section class="bg-gradient-to-br from-pink-600 to-purple-600 rounded-2xl p-6 text-white shadow-lg space-y-4">
    <div class="flex items-center justify-between">
      <div>
        <span class="text-xs uppercase text-pink-200 font-semibold tracking-wider block">Estimated Price</span>
        <span class="text-xs text-pink-100">Excludes shipping fee</span>
      </div>
      <div id="finalTotal" class="text-3xl font-extrabold">Sabah/Sarawak RM10 SEMENANJUNG MALAYSIA RM13</div>
    </div>

    <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 pt-2">
      <button type="submit" class="w-full bg-white text-pink-600 font-bold py-3 rounded-xl hover:bg-pink-50 shadow transition flex items-center justify-center gap-2">
        <span> Send Order via WhatsApp</span>
      </button>
      <button type="button" onclick="copyOrderSummary()" class="w-full bg-pink-700/60 hover:bg-pink-700 text-white font-semibold py-3 rounded-xl border border-pink-400/40 transition flex items-center justify-center gap-2">
        <span> Copy Order Text</span>
      </button>
    </div>
  </section>
</form>

