<template>
  <section>
    <h1 class="mb-7">Checks and radios</h1>

    <div class="ml-3">
      <div class="mb-3">
        <h2 class="mb-2">Checkbox</h2>
        <div class="mb-2 border p-3 rounded">
          <div class="flex">
            <label class="form-checkbox mr-3">
              Shipyard
              <input type="checkbox"/>
              <span class="checkmark"></span>
            </label>
            <label class="form-checkbox mr-3">
              <input type="checkbox" checked disabled/>
              <span>Disabled & Checked</span>
              <span class="checkmark"></span>
            </label>
            <label class="form-checkbox">
              <input type="checkbox" disabled/>
              <span>Disabled</span>
              <span class="checkmark"></span>
            </label>
          </div>
        </div>
        <div class="code">
          <code>
            &lt;<em>label</em> <i>class</i>="form-checkbox"&gt;<br>
            &nbsp;&nbsp;Shipyard<br>
            &nbsp;&nbsp;&lt;<em>input</em> <i>type</i>="checkbox"/&gt;<br>
            &nbsp;&nbsp;&lt;<em>span</em> <i>class</i>="checkmark"&gt;&lt;<em>/span</em>&gt;<br>
            &lt;<em>/label</em>&gt;<br>
            &lt;<em>label</em> <i>class</i>="form-checkbox"&gt;<br>
            &nbsp;&nbsp;&lt;<em>input</em> <i>type</i>="checkbox" <i>checked</i> <i>disabled</i>/&gt;<br>
            &nbsp;&nbsp;&lt;<em>span</em>&gt;Disabled & Checked&lt;<em>/span</em>&gt;<br>
            &nbsp;&nbsp;&lt;<em>span</em> <i>class</i>="checkmark"&gt;&lt;<em>/span</em>&gt;<br>
            &lt;<em>/label</em>&gt;...
          </code>
        </div>
      </div>

      <div class="mb-3">
        <h2 class="mb-2">Radios</h2>
        <div class="mb-2 border p-3 rounded">
          <div class="flex">
            <label class="form-radio mr-3">
              Shipyard
              <input type="radio" name="radiesito"/>
              <span class="checkmark"></span>
            </label>
            <label class="form-radio mr-3">
              <input type="radio" name="radiesito" checked disabled/>
              <span>Disabled</span>
              <span class="checkmark"></span>
            </label>
          </div>
        </div>
        <div class="code">
          <code>
            &lt;<em>label</em> <i>class</i>="form-radio"&gt;<br>
            &nbsp;&nbsp;Shipyard<br>
            &nbsp;&nbsp;&lt;<em>input</em> <i>type</i>="radio" <i>name</i>="radiesito"/&gt;<br>
            &nbsp;&nbsp;&lt;<em>span</em> <i>class</i>="checkmark"&gt;&lt;<em>/span</em>&gt;<br>
            &lt;<em>/label</em>&gt;<br>
            &lt;<em>label</em> <i>class</i>="form-radio"&gt;<br>
            &nbsp;&nbsp;&lt;<em>input</em> <i>type</i>="radio" <i>name</i>="radiesito" <i>checked</i> <i>disabled</i>/&gt;<br>
            &nbsp;&nbsp;&lt;<em>span</em>&gt;Disabled&lt;<em>/span</em>&gt;<br>
            &nbsp;&nbsp;&lt;<em>span</em> <i>class</i>="checkmark"&gt;&lt;<em>/span</em>&gt;<br>
            &lt;<em>/label</em>&gt;
          </code>
        </div>
      </div>

      <div class="mb-3">
        <h2 class="mb-2">Colors</h2>
        <div class="mb-2 border p-3 rounded">
          <div class="flex">
            <label class="form-checkbox secondary mr-3">
              Secondary
              <input type="checkbox"/>
              <span class="checkmark"></span>
            </label>
            <label class="form-radio secondary mr-3">
              Secondary
              <input type="radio" name="radiesito"/>
              <span class="checkmark"></span>
            </label>
          </div>
        </div>
        <div class="code">
          <code>
            &lt;<em>label</em> <i>class</i>="form-checkbox secondary"&gt;<br>
            &nbsp;&nbsp;Secondary<br>
            &nbsp;&nbsp;&lt;<em>input</em> <i>type</i>="checkbox"/&gt;<br>
            &nbsp;&nbsp;&lt;<em>span</em> <i>class</i>="checkmark"&gt;&lt;<em>/span</em>&gt;<br>
            &lt;<em>/label</em>&gt;<br>
            &lt;<em>label</em> <i>class</i>="form-radio secondary"&gt;<br>
            &nbsp;&nbsp;Secondary<br>
            &nbsp;&nbsp;&lt;<em>input</em> <i>type</i>="radio" <i>name</i>="radiesito"/&gt;<br>
            &nbsp;&nbsp;&lt;<em>span</em> <i>class</i>="checkmark"&gt;&lt;<em>/span</em>&gt;<br>
            &lt;<em>/label</em>&gt;
          </code>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: "ChecksRadios",
};
</script>