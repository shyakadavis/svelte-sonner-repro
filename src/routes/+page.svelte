<script>
	import { Toaster, toast } from 'svelte-sonner';
</script>

<Toaster richColors closeButton />

<button onclick={() => toast.info('Info')}> Info </button>
<button onclick={() => toast.success('Success')}> Success </button>
<button onclick={() => toast.warning('Warning')}> Warning </button>
<button onclick={() => toast.error('Error')}> Error </button>
