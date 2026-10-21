<script type="module">
  import { createClient } from "https://esm.sh/@supabase/supabase-js@2";

  const supabase = createClient(
    "https://iddzstbhsenlfyoszobf.supabase.co",
    "sb_publishable_zSuVYF5Mcydl_5eNvip9cw_tqZ6461p"
  );

  async function showItemsWithTag(tag) {
    const { data, error } = await supabase
      .from("items")
      .select("id, title, tags")
      .contains("tags", [tag]);

    if (error) {
      console.error(error);
      return;
    }

    document.querySelector("#results").innerHTML = data
      .map(item => `<p>${item.title}</p>`)
      .join("");
  }

  showItemsWithTag("animals");
</script>

<div id="results"></div>
